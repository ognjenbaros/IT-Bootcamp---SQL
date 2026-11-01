
## Ja sam Ognjen Baroš i ovo je moj SQL Gate projekat.


# Opis fajlova
1. SQL deo A ---> 'Део А' Gate projekta
2. SQL deo B ---> 'Део Б' Gate projekta, sadrži SQL upite korišćenje za pravljenje izveštaja report.md
3. report.md ---> izveštaj za sezonu 2024/25
4. SQL deo C ---> 'Део В' Gate projekta
5. SQL deo D ---> 'Део Г' Gate projekta



# Pretpostavke:

 DEO B, pitanje 5)
dodao sam own_goal u satistiku za najbolje strelce i asistente, 
jer, iako autogol nije dobra stvar, 
ipak jeste postignut gol i zapisuje se u statistiku.


DEO C

U pitanju je zvezdasta struktura sa tabelom fact_card u središtu
i tabelama dim_team, dim_player i dim_referee kao granama.
Povezane su na sledeći način:

    fact_card.team_id = dim_team.team_id
    fact_card.player_id = dim_player.player_id
    fact_card.referee_id = dim_referee.referee_id
