# EmployeeWebApp

EmployeeWebApp is a full-stack web application that leverages a variety of powerful technologies. Built using the Spring Framework, Thymeleaf, and Hibernate, it provides users with an intuitive interface for managing employee records within a company. With the ability to perform a wide range of CRUD operations on employee data, it offers a comprehensive solution for companies of all sizes.

## Features

- View a list of all employees in the company
- Search for an employee by name, department, or job title
- Create a new employee and add them to the database
- Update an existing employee's information
- Delete an employee from the database
- View and manage employee salaries, including updating and deleting salaries
- View and manage employee job titles, including adding new job titles and updating existing ones
- View and manage employee departments, including adding new departments and updating existing ones
- See the average salaries for the entire company, by gender, by job title, and by department
- Determine and view gender pay gaps across the company

## Technology Stack
- Java
- Spring Boot
- JPA
- Hibernate
- Thymeleaf
- MySQL
- HTML
- CSS

## Installation

1. Clone the repository
    ```
    git clone https://github.com/AliG-123/JPAProjectFinal.git
    ```
2. Import the project into your IDE
3. Configure the database connection in `src/main/resources/application.properties`
4. Run the application from your IDE 

## Usage

1. Navigate to `http://localhost:8080/employees'
2. Click the "Create Employee" button to create a new employee
3. Fill out the form with the employee's information and click "Save"
4. Click the "Edit" button on an employee's details page to update their information
5. Click the "Delete" button on an employee's details page to delete them from the database
6. To manage employee salaries, job titles, or departments, navigate to the corresponding pages and use the available features.

<details>
<summary>Click to view testing results snapshots</summary>

- GenderService Test
![image](https://user-images.githubusercontent.com/117417937/222679893-2ca0f09d-bf3e-4c7f-9af9-cf84fdb7d598.png)

- JPA Project Application Tests
![image](https://user-images.githubusercontent.com/117417937/222782226-04b1c474-903c-40c3-81ae-7f1d4588148f.png)

- EmployeeService Test
![7f0a1e33-3263-4e96-a33a-39730a9a219c](https://user-images.githubusercontent.com/117417937/222685063-768c6e93-5438-4215-9c07-8de8e6a6cd98.jpg)

- SalaryService Tests
![image](https://user-images.githubusercontent.com/117417937/222699712-3536714e-1843-4205-9213-5905b3a158ef.png)

- Staff Service Tests
![97ce0628-510a-4aba-84e5-db9a1133cd42](https://user-images.githubusercontent.com/117417937/222716642-ba6498ec-0993-4d41-b5f7-d97b33aafbe7.jpg)

</details>

## Contributing

Contributions to JPAProjectFinal are welcome! Please fork the repository and submit a pull request with your changes.

## License

JPAProjectFinal is released under the MIT License. See `LICENSE` for details.

I hope this helps!



