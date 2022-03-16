# fastapi-songs

A simple application written using [FastAPI](https://fastapi.tiangolo.com/). 

The application has the following endpoints:

1. [http://localhost:8000/](http://localhost:8000/) displays the index page
2. [http://localhost:8000/songs](http://localhost:8000/songs) displays the song list

## Want to use this project?

1. Fork/Clone

2. Create and activate a virtual environment:

    ```sh
    $ python3 -m venv venv && source venv/bin/activate
    ```

3. Install the requirements:

    ```sh
    (venv)$ pip install -r requirements.txt
    ```

4. Initialize the database:

    ```sh
    (venv)$ python init_db.py
    ```

5. Run the server:

    ```sh
    (venv)$ uvicorn main:app --reload
    ```
    
 6. Navigate to [http://localhost:8000/](http://localhost:8000/) in your favorite web browser.