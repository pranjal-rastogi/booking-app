

## Project Description

The **Go Conference Booking Application** is a command-line tool that allows users to book tickets for the "Go Conference." Users enter their details and ticket quantity, and the app confirms their booking. It uses concurrency to handle multiple bookings, struct-based data storage for user details, and validates inputs for a smooth booking experience.

---

### `README.md`

```markdown
# Go Conference Booking Application

A command-line application in Go for booking tickets to the "Go Conference." Users can book tickets by entering their details, and the application will confirm the booking and send a simulated confirmation email.

## Features

- **User Input and Validation**: Collects and validates user details and ticket quantity.
- **Concurrency**: Utilizes goroutines to simulate sending confirmation emails concurrently.
- **Booking Management**: Tracks available tickets and displays booking details.

## Getting Started

1. Clone the repository.
2. Run the application:

   ```bash
   go run main.go

3. Follow the prompts to book your tickets.
```

## Example Code

```go
go sendTicket(userTickets, firstName, lastName, email)
```


