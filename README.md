1. Go to settings, add flights
2. Go to url, add flights.urls
3. Create urls.py
4. Add urlpatterns

-   `python manage.py makemigrations`
-   `python manage.py migrate`

-   `python manage.py shell`
-   `from flights.models import Flight`
-   `f = Flight(origin="New York", destination="London", duration=415)`
-   `f.save()`

-   `flights = Flight.objects.all()`
-   `flight = flights.first()`
-   `flight.id`
-   `flight.origin`
-   `flight.delete()`

-   `from flights.models import *`
-   `jfk = Airport(code="JFK", city="New York")`
-   `jfk.save()`
-   `f = Flight(origin=jfk, destination=lhr, duration=415)`

-   `lhr.arrivals.all()`

1. Go to urls.py add default route
2. Go to views.py
3. Create templates/flights/layout.html
4. Create index.html in flights

-   `python manage.py runserver`
-   `Airport.objects.filter(city="New York")`
-   `Airport.objects.get(city="New York")`

-   `python manage.py createsuperuser`

1. Go to admin.py in flights
2. Go to flights/urls.py add path
3. Go to views.py, add flight function
4. Create flight.html
5. Add Passenger model
6. Go to views.py, add passenger
7. Go to urls.py, add book

# Start django project

-   `django-admin startproject airline`
-   `cd airline`
-   `code .`
-   `python manage.py startapp flights`
#   t e s t i n g - c i - c d  
 