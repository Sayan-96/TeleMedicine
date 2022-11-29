# Telemedicine Management System

This is a simple telemedicine project which helps doctor and patients to connect using video conferencing and chat.
Below is the basic flow of the project.

Doctor logs in , Patient logs in by filling his issues.
Both go in to video conference call and discuss issues.
Doctor fills advice.
Patient can print advice after the call.
Doctor and patients can also send chat messages to each other.
Patients can also share documents with doctor.

# Features:

Application supports Multi doctor and Multihospital.

Medication can be filled by Doc.

Patient can input problems.

Chat message support between doctors and patients.

Patients can share document with doctors while conferencing.

Tracks time spent per call between doctor and patient.

# Tools Used:
Front-end: HTML, Python, CSS

Back-end: MySQL, PHP

# Screenshots:

## Home
![1](https://user-images.githubusercontent.com/78608059/204636790-9aa09b8f-0c5a-405e-839c-74d432cb821f.png)
## Login Page
![2](https://user-images.githubusercontent.com/78608059/204636912-53bb8b8e-bd82-4966-a9d7-2d7ac6492073.png)
## Feedback
![3](https://user-images.githubusercontent.com/78608059/204643682-b62e594a-0c08-4efd-ab6b-96859eae9473.png)
## About Us
![4](https://user-images.githubusercontent.com/78608059/204643717-e84957f2-695e-4153-b9b7-6f20238c1c25.png)
## Admin Login Page
![5](https://user-images.githubusercontent.com/78608059/204643720-5a1dbd10-10d8-4248-b88d-195f08a13582.png)
## Doctor Login Page
![6](https://user-images.githubusercontent.com/78608059/204643724-dc85db6c-6afc-41b5-821d-63063e5f6c4d.png)
## Patients Login Page
![7](https://user-images.githubusercontent.com/78608059/204643729-3b57fc65-bec9-49e6-bc60-27033da0ab17.png)
## Doctor Dashboard
![8](https://user-images.githubusercontent.com/78608059/204643732-9f876314-7c71-435e-b715-24320de7d7b2.png)
## Patient Records
![9](https://user-images.githubusercontent.com/78608059/204643736-3f0f49d2-1982-4283-88ee-46d90603221f.png)
## Appointment Dashboard
![10](https://user-images.githubusercontent.com/78608059/204643777-65aa55cc-c4b1-4a3b-88ee-83c7137f86b8.png)
## Admit Patient
![11](https://user-images.githubusercontent.com/78608059/204643782-994eace3-427a-4f61-ba1c-9b8ba9c2f3c0.png)
## Total Count
![12](https://user-images.githubusercontent.com/78608059/204643784-887af7aa-1319-4c41-a19f-34cb40e5bf8c.png)
## Patient Dashboard
![13](https://user-images.githubusercontent.com/78608059/204643788-0d24d9e8-9d81-495b-8d8d-d9f67b1dd28d.png)
## MAP
![14](https://user-images.githubusercontent.com/78608059/204643793-6dc51d43-ea78-4e5e-99df-ca6d4689e4d6.png)
## Discharge Details
![15](https://user-images.githubusercontent.com/78608059/204643802-97bd17c6-06a2-4a52-8ee3-fde597342e67.png)
## Patient Details
![16](https://user-images.githubusercontent.com/78608059/204643804-901c0105-0f32-4d98-98f2-5fc876328ae3.png)
## Bills
![17](https://user-images.githubusercontent.com/78608059/204643807-7cb373e4-4d2f-40bc-8916-b88bb4d07f76.png)


# How to Use:
1. User Login: This contains all the tools and options required by any user who's willing to book a hotel room.
2. Admin Login: This contains all the controls that an administrator has to manage the hotel including adding and deleting rooms.
3. Image Gallery: This contains image gallery of the rooms in the hotel.
4. Room Details: Thism rate card.
5. Room Booking History: This is the previous room bookings history stored for future references.

# Working:
1. A new user sign up and creates a new account. Then the user logins using the email and password.
2. After logging in, user books a room.
3. The room booking request is sent to hotel administrator. This is the admin job to either confirm or delete the request. User can also delete his/her room booking request if any changes in plan happens.
4. After the room is confirmed, user will get an option to pay the amount as per the services. 
5. After the user checks out, user will pay the amount and an entry will be made to room booking history.

# Expalanation how to interect patient with Telemadicine Samrt Doctor
1. Patients interact with Telemedicine Smart Doctor by digital device like the Raspberry Pi, smart phone, tab, pad, pod etc.

2. Patient face detection is completely based on the environment, in the meanwhile we will use ML services like Amazon Recognition, Amazon Sazemaker etc.

3. The vital sign is real time displayed in the dashboard (An alert will be showed and an email notification will be sent if there is any abnormal data)

4. The diagnosis result will be stored on Amazon RDS with the name of the medical record.

5. The patient will get the diagnosis immediately and if the patient has a serious condition it will pass the online doctor.

# Conclusion
The running cost of Apollo Clinicals is very low cost and highly scalable (100% serverless). All conversations, data and diagnostic results are stored in Amazon RDS. In serious condition targets to remind and refer patients to the real doctor. The real doctor diagnostic results can help the system learn and improves the diagnostic accuracy with AWS Machine Learning. It will save money, time and strength of a people. At last we say, Telemadicine Smart Doctor makes the world more safe.
