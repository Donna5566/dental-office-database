# Dental Office Database Requirements

## Entities and Attributes
### Patient
-PatientID (Primary Key)
-FirstName
-LastName
-DateOfBirth
-Phone
-Email
-Address

### Appointment
- AppointmentID (Primary Key)
- AppointmentDate
- AppointmentTime
- Sstatus
- PatientID
- DentistID

### Service
- ServiceID (Primary Key)
- ServiceName
- Description
- Cost

### Dentist
-DentistID (Primary Key)
-FirstName
-LastName
-Specialty

### Treatment
TreatmentID (Primary Key)
- TreatmentDate
- Notes
- AppointmentID
- ServiceID
- DentistID

### Payment 
-PaymentID (Primary Key)
 -Amount 
-PaymentDate 
- PaymentMethod
- PatientID 
