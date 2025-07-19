VaxTrack is a comprehensive vaccination management system that allows users to register and log in as a patient, an admin, or a vaccine center. The system provides authentication for patients and centers via OTP using sessions in Firebase. The primary goal of VaxTrack is to create a centralized platform that enables efficient management of vaccination records, appointment scheduling, and vaccine stock monitoring. The target audience for VaxTrack includes individual users who seek to manage their vaccination information, vaccination centers that need to track and update patient vaccination status, and healthcare administrators responsible for overseeing the vaccination program.
<img width="874" height="381" alt="image" src="https://github.com/user-attachments/assets/b79a1d09-f02e-44f4-8d18-55eb9aef7ce4" />
User (Patient) Flow:
   - VaxTrack allows users to register and create an account by providing their phone number.
   - The registration process includes filling out a form with personal details, which are then saved in the backend database.
<img width="855" height="374" alt="image" src="https://github.com/user-attachments/assets/b3cd65d7-4bfc-4300-b882-22a3c312ea3d" />
- Upon registration, users receive a one-time password (OTP) via SMS for authentication, leveraging the Firebase platform.
- <img width="331" height="437" alt="image" src="https://github.com/user-attachments/assets/0352fb4c-addf-46cb-8b23-e9badd9b928c" />
  - Users can then log in to the application using their registered phone number and the received OTP.
   - The user's login session is securely stored using cookies and session handling mechanisms, ensuring a seamless and secure user experience.
   - <img width="975" height="418" alt="image" src="https://github.com/user-attachments/assets/16d5eb38-087e-4a70-8bbc-79ccbdb3ee57" />
- Users can navigate to the "Search Appointment" functionality on the homepage and enter their location (Pin code) to find available vaccination centers in their area.
- <img width="975" height="574" alt="image" src="https://github.com/user-attachments/assets/8a2422db-b8e3-4002-bb5a-2e93d87ca2b2" />
   - The application retrieves the details of the vaccination centers from the backend database and presents the user with a list of options.
  - Users can then select a preferred vaccination center and proceed to book an appointment.

 - During the appointment booking process, users are prompted to choose a suitable appointment date from the available slots.
 - <img width="975" height="571" alt="image" src="https://github.com/user-attachments/assets/8be746a2-ded1-43b8-a72e-2253fa93b6f3" />
 -View More Page shows additional details.
<img width="576" height="650" alt="image" src="https://github.com/user-attachments/assets/f2303487-daad-4910-b5e4-8625a42ef4fa" />
   - Upon confirming the appointment, the details are saved in the "appointment" table of the database, and an available vaccine is automatically assigned to the user.
   - <img width="745" height="432" alt="image" src="https://github.com/user-attachments/assets/9b80e719-68e1-4ca0-81e1-dfb7c97976de" />
   - After a successful vaccination, users can download their vaccination certificate in PDF format, provided they are logged in to the application.
   - <img width="556" height="601" alt="image" src="https://github.com/user-attachments/assets/1fbbd70a-b7e8-4e1e-b687-6af61f5e4d47" />
   - Users can access their vaccination history and view their vaccination records through their account page and edit their details using update functionality.
   - <img width="910" height="436" alt="image" src="https://github.com/user-attachments/assets/fc6b86be-12c1-4e02-9cc6-c27df8a9ce0d" />

Vaccine Center Flow:
   - Vaccine centers can log in to the VaxTrack application using their registered phone number and receive an OTP for authentication.

<img width="975" height="418" alt="image" src="https://github.com/user-attachments/assets/31ae810c-7fae-4d46-b10a-e80f0a551b83" />
- Once logged in, vaccine centers can view the details of their center, including all the appointments and patient information scheduled for their location.
- <img width="975" height="241" alt="image" src="https://github.com/user-attachments/assets/41e9aae6-71f0-4a6f-9c56-31f903011063" />
 - Vaccine centers can update the vaccination status of their patients as the vaccination process progresses.

<img width="991" height="435" alt="image" src="https://github.com/user-attachments/assets/09f52a4a-d999-4f40-b821-8b8c017b7d3d" />
   - This functionality enables vaccine centers to efficiently manage their vaccine stock and maintain accurate records of the vaccination process.
Admin Flow:
   - VaxTrack provides an admin dashboard accessible only to authorized administrators using admin username and password.
- Administrators can view everything related to the vaccination program, including details of all registered users, appointment records, and vaccine center information.
- <img width="975" height="494" alt="image" src="https://github.com/user-attachments/assets/ba2a03cd-9e6a-40bf-93d4-8815c23640fd" />
<img width="975" height="553" alt="image" src="https://github.com/user-attachments/assets/5629f8f8-a7cb-424d-8310-c43fe7df221a" />
<img width="975" height="561" alt="image" src="https://github.com/user-attachments/assets/8bdd34a0-b26a-4834-a6c4-81a7aa739b58" />
<img width="975" height="567" alt="image" src="https://github.com/user-attachments/assets/8891ad01-015b-4a31-ba71-e151e1eb70fb" />
<img width="975" height="567" alt="image" src="https://github.com/user-attachments/assets/6d9c4d21-ec68-4b3a-a1cc-52aba10161e0" />
- The admin dashboard offers insights into vaccination data, allowing healthcare administrators to make informed decisions and optimize the vaccination program.
-Admin can register a new vaccine via dashboard.
<img width="975" height="543" alt="image" src="https://github.com/user-attachments/assets/4c5665a7-a003-4cbe-a69c-10465dd0d9b0" />
-Admin can also delete Patients records

<img width="975" height="619" alt="image" src="https://github.com/user-attachments/assets/4e60b5e7-daee-4c04-86de-78c905c889ac" />












