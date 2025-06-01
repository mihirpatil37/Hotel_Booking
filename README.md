
# Hotel Booking Application

This project is a **command-line hotel booking system** built using Python and Pandas. Users can view available hotels, make bookings with credit card validation and security authentication, and receive a reservation ticket.

## Features

- Display hotel listings with availability
- Book hotels only if rooms are available
- Validate credit card data from external CSV
- Authenticate credit card with a password
- Generate and display a reservation confirmation

## Project Structure
```
Hotel_Booking/
├── cards.csv # Card information for validation
├── card_security.csv # Card password data for authentication
├── hotels.csv # Hotel data including availability
├── main.py # Main application script
├── Requirements.txt # Required dependencies
```

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/mihirpatil37/Hotel_Booking.git
cd Hotel_Booking
```
2. **Create and activate a virtual environment**

```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. **Install dependencies**

```bash
pip install -r Requirements.txt
```
## How to Use
Run the main application:
```bash
python main.py
```
- You will be shown a list of available hotels.
- Input the hotel ID to make a booking.
- Enter credit card number and proceed with validation and authentication.
- If successful, a booking confirmation will be generated.

### Screenshots Section
## Screenshots

### ✅ Room Available & Booking Successful  
[View Full Image](https://github.com/mihirpatil37/Hotel_Booking/blob/master/Room_Available_Booking_Success.PNG)  
![Room Available](https://github.com/mihirpatil37/Hotel_Booking/raw/master/Room_Available_Booking_Success.PNG)

### ❌ Room Not Available  
[View Full Image](https://github.com/mihirpatil37/Hotel_Booking/blob/master/Room_Not_Available.PNG)  
![Room Not Available](https://github.com/mihirpatil37/Hotel_Booking/raw/master/Room_Not_Available.PNG)

## Example Data (CSV Files)

### hotels.csv
```csv
id,name,city,capacity,available
134,Tourist Sunny Apartment,Anchorage,4,no
188,Snow Palace,New Delhi,5,yes
655,City Break Inn,Porto-Novo,3,no
```
### cards.csv
```csv
number,expiration,holder,cvc
1234567890123456,12/26,JOHN SMITH,123
```
## card_security.csv
```csv
number,password
1234567890123456,mypass
```

## Author
**Mihir Patil**  
[GitHub Profile](https://github.com/mihirpatil37)











