# Albums and Artists

Your task is to complete a Flask app which contains 2 classes that have a One To Many relationship.

- Albums and Artists

We have provided a start point for you. 

## Task

In your application you should be able to perform the following actions:

* Be able to list all albums.
* View a single Albums details including stock level
* Be able to delete an album.


#### Setting up the app

* Step 1: Create a database

```bash
createdb album_manager
```

* Step 2: Run the sql file

```bash
psql -d album_manager -f db/album_manager.sql
```

* Step 3: Seed the database

```bash
python3 console.py
```

* Step 4: Run the app

```bash
flask run
```

You app should now be available at `http://localhost:5000`




