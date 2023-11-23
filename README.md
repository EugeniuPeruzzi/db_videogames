#### SELECT

1. Selezionare tutte le software house americane (3)
    - ```SELECT * FROM software_houses where country = 'United States';```

2. Selezionare tutti i giocatori della cittÃ di 'Rogahnland' (2) 
    - ``` SELECT * FROM players WHERE city = 'Rogahnland'; ```

3. Selezionare tutti i giocatori il cui nome finisce per "a" (220)
    - ``` SELECT * FROM players WHERE name LIKE '%a'; ```

4. Selezionare tutte le recensioni scritte dal giocatore con ID = 800 (11)
    - ``` SELECT * FROM reviews WHERE player_id = 800; ```

5. Contare quanti tornei ci sono stati nell'anno 2015 (9)
    - ``` SELECT COUNT(*) FROM tournaments WHERE year = 2015; ```

6. Selezionare tutti i premi che contengono nella descrizione la parola 'facere' (2)
    - ``` SELECT * FROM awards WHERE description LIKE '%facere%'; ```

7. Selezionare tutti i videogame che hanno la categoria 2 (FPS) o 6 (RPG), mostrandoli una sola volta (del videogioco vogliamo solo l'ID) (287)
    - ```sql
SELECT DISTINCT id 
FROM category_videogame 
WHERE category_id = 2 OR category_id = 6;



8. Selezionare tutte le recensioni con voto compreso tra 2 e 4 (2947)
    - ```  ```