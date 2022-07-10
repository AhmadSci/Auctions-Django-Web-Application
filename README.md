
# Auctions-Django-Web-Application

A Django web application that allows users to auction off their stuff


# Features

- Bidding on listings
- Listing new items
- Adding Listings to your watchlist
- Winning/Losing an Auction
- Commenting on active listings
- Categories to filter listings

---

# [Demo](https://ahmedsauctions.herokuapp.com/)

# Setting it up
1. Create and activate python virtual environment

    ```bash
    py -m venv myvirtualenv
    myvirtualenv\Scripts\activate
    ```

1. Install requirements via pip: `pip install -r requirements.txt`
2. Make migrations and migrate the database

    ```bash
    python manage.py makemigrations network
    python manage.py migrate
    ```

3. Run `python manage.py createsuperuser`
4. Create your admin user
5. Run `python manage.py runserver`
6. Add categories from the admin panel `http://127.0.0.1:8000/admin/auctions/categories/add/`