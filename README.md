

# COVID Bed Availability and Booking System

This system was developed to address the critical shortage of hospital beds during the COVID-19 pandemic. It allows authorities to manage hospital beds and citizens to book available beds based on their condition. The system ensures that critical patients get immediate attention and can book a hospital bed while others might be advised for home quarantine or added to a waiting list.

## Features

### For Authorities (Admins)
1. **Login and Authentication**: Admins need to log in with an authority name and password to access the system.
2. **Hospital Management**:
   - **Add Hospital**: Admins can add new hospitals to the system.
   - **Delete Hospital**: Admins can delete hospitals from the system.
   - **Display List of Hospitals**: Admins can view a list of hospitals in the city.
3. **Patient Management**:
   - **Display Patients**: Admins can view a list of patients awaiting bed allocation.
   - **Discharge Patients**: Admins can discharge patients and confirm bed allocations.
   
### For Citizens
1. **Patient Registration**: Citizens can enter their details, including their health condition (e.g., CT score, O2 level, comorbidity).
2. **Check Bed Availability**: Based on the citizen's region and condition, the system displays hospitals with available beds.
3. **Home Quarantine or Bed Allocation**: Depending on the patient's criticality, they are either advised to home quarantine or allocated a bed in a hospital.
4. **Waiting List**: If no beds are available, citizens are added to a waiting list.
5. **Booking Bed**: Citizens can book a bed in a hospital if it's available, based on their health condition and urgency.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/covid-bed-booking-system.git
   cd covid-bed-booking-system
   ```

2. **Install dependencies**:
   If you have any specific dependencies, install them. For this system, you might not need external packages unless it's using a database or web framework. However, if there are any dependencies, list them here.

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the system**:
   The system is designed to run as a simple text-based application. You can run it from your terminal.
   
   ```bash
   python main.py
   ```

---

## Usage

### Admin Login

1. The admin first needs to authenticate using an authority name and password.
2. Once logged in, they can manage hospitals (add, delete, display).
3. Admins can display patients waiting for a bed and discharge them.

### Citizen Functionality

1. Citizens will enter their personal details (name, age, contact number, CT score, O2 level, comorbidity status).
2. They can then select their region (Mumbai, Pune, or Nashik).
3. The system will display hospitals in the city with available beds.
4. If the beds are available, citizens can book them. If no beds are available, they are added to the waiting list.
5. Critical cases may be allocated a bed if available.

---

## Example Flow

1. **Admin Login**: Admin enters their credentials and is logged into the system.
2. **Add/Manage Hospital**: Admin adds new hospitals, deletes old ones, and lists hospitals.
3. **Citizen Registration**: A citizen enters their details, and based on their CT score and oxygen level, the system suggests whether they should quarantine at home or book a hospital bed.
4. **Hospital Bed Booking**: The citizen chooses a hospital with available beds and books a bed if necessary.
5. **Discharge and Confirmation**: Admin discharges patients after they recover and updates the system accordingly.

---


## Technologies Used

- Python 3.2
- Text-based User Interface (TUI)
- Database: MySQL

---

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please fork the repository, make your changes, and submit a pull request.

---


Let me know if you need any further adjustments or additions!
