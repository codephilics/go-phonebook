# GoAPI


## To run the project
Create `.env` and run `docker-compose up`

## ENV
POSTGRES_URL=postgres://postgres:yourpassword@postgres/postgres?sslmode=disable
PORT=

## Routes

		Name("HomePage").
		Methods("GET").
		Path("/").
    
		Name("ServeSignupForm").
		Methods("GET").
		Path("/register").
	
		Name("RegisterAccount").
		Methods("POST").
		Path("/register").
	
		Name("ServeLoginForm").
		Methods("GET").
		Path("/login").

		Name("Login").
		Methods("POST").
		Path("/login").

		Name("Logout").
		Methods("GET").
		Path("/logout").
