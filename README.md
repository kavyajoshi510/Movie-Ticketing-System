# Movie Ticketing System

## System Requirements

* Ruby version: 3.4.1 
* Rails version: 8.0.1

## Key Gems

- **Devise** - Authentication framework for Rails  
- **Importmap-Rails** - Manages JavaScript dependencies without Webpack  
- **Capybara and Selenium-WebDriver** - Used for system testing  
- **Brakeman** - Static analysis tool for security vulnerabilities  
- **Dotenv-Rails** - Loads environment variables from `.env`  
- **Kamal** - Enables deployment as a Docker container  
- **Thruster** - Enhances Puma server performance with caching and compression

## Getting Started

### System dependencies
```
bundle install
```

### Database creation and initialization
```
rails db:migrate
rails db:seed
```
### Start application
```
rails server
```

### Deployed application link
http://fargate-elb-1230748689.us-east-1.elb.amazonaws.com


### Repository link
https://github.ncsu.edu/kjoshi4/Program-2-Ruby-on-Rails.git


## How to run the test suite
We have implemented comprehensive tests for the movie functionality. To run specific test suites:
```
rspec spec/models/movie_model_test.rb
rspec spec/controllers/movies_controller_test.rb
```
Current Output:
```
rspec spec/models/movie_model_test.rb
........

Finished in 1.16 seconds (files took 1.7 seconds to load)
8 examples, 0 failures


rspec spec/controllers/movies_controller_test.rb
.......

Finished in 2.4 seconds (files took 2.05 seconds to load)
7 examples, 0 failures
```

## Testing Features

### Admin Features  

### 1️⃣ Log in  
Admins can log in with:  
**Username:** `admin@admin.com` | **Password:** `admin`  

### 2️⃣ Manage Users 
Manage users via the Users Dashboard with options to:  
➤ Add a new user | View details  | Edit info  | Delete a user  

### 3️⃣ Manage Movies 
The Movies Dashboard allows admins to:  
➤ Add a new movie | View details | Edit info | Delete a movie  

### 4️⃣ Manage Shows 
Manage all scheduled shows using the Shows Dashboard:  
➤ Add a new show | View details | Edit info | Delete a show  

### 5️⃣ Manage Tickets 
The Tickets Dashboard provides options to:  
➤ Add a new ticket | View ticket details  

### User Features  

### 1️⃣ Sign Up / Log In  
- Click "Log In" on the homepage and then "Sign Up" and fill in the required details to create an account.  
- Use the "Log In" button on the homepage to access your account.  

### 2️⃣ View Booking History  
- Click "Booking History" on the user dashboard to see all bookings.  

### 3️⃣ Browse & Book Movies  
- Click "Movies" to explore all available movies for booking.  
- Scroll through currently available movies.  

#### Select Show & Showtime  
- Click "Show" on a movie to view available show dates.  
- Select a date to see all available showtimes for that day.  

#### Book Tickets  
- Choose a showtime to proceed to the **Booking Confirmation** page.  
- Click "Confirm Booking" to finalize your ticket purchase.  


### Additional Features  
#### Search function for admin:
1. In the Tickets Dashboard, an option is available to filter by a specific movie.
2. Admins can select a movie from a dropdown, click the Filter button, and view a list of users who booked tickets for the selected movie, along with the showings.



## Team Members

- **Kavya Lalbahadur Joshi**
- **Jap Ashokbhai Purohit**
- **Kenil Mineshbhai Patel**

