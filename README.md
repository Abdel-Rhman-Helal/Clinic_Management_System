# Clinic_Management_System
it is a Simple C Project Without GUI , to Simulate a Clinic Management System Using Linked List

#### there is a two mode 
1. Admin mode
2. User mode

#  In admin mode : 

The system asks for password, the default password is 1234. The system allows 3 trails for the password 
entry, if the entered password was incorrect for 3 consecutive times

1. Add new patient record:

To add a new patient, the user shall admin shall enter these basic information: name, age, gender and 
ID. The ID shall be unique for the user, if the entered ID is already exists, the system shall reject the 
entry.

2. Edit patient record

By entering patient ID the system shall checks if the ID exists, the system shall allow the user to edit the 
patient information. If not, the system shall display incorrect ID message.

3. Reserve a slot with the doctor

By default there are 5 available slots, 2pm to 2:30pm, 2:30pm to 3pm, 3pm to 3:30pm, 4pm to 4:30pm
and 4:30pm to 5pm. Upon opening of this window, the system shall display the available slots. The 
admin shall enter the patient ID and the desired slot. The reserved slot shall not appear again in the next 
patient reservation.

4. Cancel reservation.

The admin can cancel a reservation by entering the patient ID. This reservation shall be shown again in 
the available slots window.

5. Delete Patient 

By entering patient ID the system shall checks if the ID exists, the system shall allow the user to Delete the 
patient information. If not, the system shall display incorrect ID message.

# In the user mode:

There is no password. The system allows the following features:

1. View patient record.

By entering the patient ID, the system shall show the basic information for the patient.

2. View today’s reservations.

In this view, the system shall print all reservations with the patient ID attached to each reservation slot
