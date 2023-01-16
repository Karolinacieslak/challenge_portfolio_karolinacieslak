# Task 1
## Subtask 1
9/10 points
## Subtask 2
Hi my name is Karolina! I decided to participate in Dare IT challenge tester manualny because I want to challenge my belief that I can't learn software testing :-)

My main goals are:
* to learn and understand what is software testing and why it is important
* build portfolio that I can present to potential employers
* have fun :-)

## Subtask 3
**1. Na czym polega aplikacja Scout Panel? Do czego służy?**

Aplikacja Scout Panel jest to aplikacja dla skautów piłki nożnej, która umożliwia przeglądanie wskaźników, umiejętności i pozycje zawodników. W tym przypadku skauci to nie harcerze tylko tacy “łowcy talentów”.

**2. Jakie funkcjonalności znajdują się w tej aplikacji? Do czego służą, czy są intuicyjne, czy może byś coś zmienił_a?**

App's features (functionalities):

* logowanie sie i wylogowanie sie
* zmiana jezyka aplikacji
* dodawanie zawodnika - formularz zawodnika (shortcut)
* lista zawodnikow
* CVS file download
* print
* page view adjustment
* add match option
* add report option (match reports)
* add link to youtube
* filters (players)

Most of those functionalities are clear and intuitive for me. I know how to use them and what I can expect from them. However, the overall experience is not a good user experience. The tool could use some **tooltips and simple onboarding when we log in or sign up to help with the general UI and functionalities**. It could help us undertsand how to use it and how to perform some of the actions or what to expect when used. For a better user experience and fast tool adoption.

**3. Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**

Nope, I don't like the interface. It could be better, more intuitive and self-explanatory design. The iterface seems chaotic to me.

**4. Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu)**

So for me it is intuitive and clear how to add a new player on the main page, via shortcut. However, I noticed that it is not possible directly fromt he Players page - I wonder why is that? Seems not correct to me. Once you go to the _Players_ tab, and see the players list, you should be able to add a player there as well, so _add player_ button would work here. So definitely a NO for this solution - user should eb able to ad a player also from the players tab, not only via shortcut on the maion page.

**5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku.**

* As above, lack of _add player_ button in the Players tab seems to me like a bug or a mistake, or just bad experience. Doesn't feel _natural_ and intuitive to me. Also, the add player form itself seems buggy, for example adding height accepts any number, even though it says cm only. For example, I put 2 and it is correct, and if I put 2000 it is also correct. Doesn't feel right to me. There should be a ,imit set on the height, at least some error helping us see the mistake between 200 and 2000.

* In general the form accepts anything even blablabla, so does not indicate any erorrs in mandatory and non mandatory fields, not sure if this is expected, seems not correct to me, especially the email field. _Laczy nas pilka_, _90 minut_ i Facebook accept anything as well, and I have no idea what should I use in those fields - links?

* And of course once I use bull... in all the fileds (player form), I get an error saying **cannot add player** after clicking submit. No information why or what can I do to improve my form and be able to submit it. If I do not know what I did wrong in my form, I can't improve it. **Clear error indication and instructions which fields are not correct is absolutely necessary here. Looks like a bug to me. And horrible user experience.** (vaidation error in devtools)

* On the main page the _cards_ (?) are not distributed equaly and look chaotic. Also why is the card _scouts panel_ on the main page not clickable - it is useless and not clear how to use it. Why does it have a link to Dev team contact on slack, if it says _Player, match and report management panel_? I am completely confused and no idea why and how to use this. It feels liek it is a big again and it is not clickable and does not allow me to actually see what it says - player, match and report manag. panel (the scouts panel).

* When you select a player and the _matches_ tab, you get option to _create report_ & _start report_ in Actions - why? More, both thake you to two different and confusing tabs, where I have no idea what to do. 

**_Karol_**
