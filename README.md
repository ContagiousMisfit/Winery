# winery_app

![winery](https://github.com/user-attachments/assets/de760c99-7fe7-49f1-8b34-5f85eca9480c)

Winery cross platform application written in flutter
<h3>Technologies</h3>

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

<h2> Core concepts applied </h2>

<ul>
    <li> ⚡ <b> Data Persistence: </b> 
     Implemented mechanisms for storing data, ensuring that the application can retain user data between sessions. In the context of the project, using SQLite helps maintaining a seamless user experience.
    </li>
<br>
<li> ⚡ <b> API Consumption:</b> Integrated external RESTful APIs to fetch and send data to a server. This involved parsing JSON responses, error handling, and ensuring smooth data retrieval, which is vital for any application that interacts with remote data sources.
</li>
  <br>
  <li> ⚡ <b> Best Practices in Architecture:</b> Followed clean coding standards such as the SOLID principles and applied design patterns like Repository Pattern to keep the business logic separate from the UI and data layers. This made the codebase easier to maintain, test, and scale as more features were added.
</li>
  <br>
<li> ⚡ <b> Clean Feature-Based Architecture with Layers of Separation of Concerns:</b> Organized the project into feature modules (e.g., Catalog, Management) and clearly defined layers such as UI, business logic, and data. This structure allows for scalability and ease of maintenance, especially in larger projects. Each feature is self-contained, ensuring better code readability and reducing the risk of conflicts when adding new functionalities.
</li>
  <br>
  <li> ⚡ <b> Stateful and Stateless Widgets:</b> By deciding when to use stateless widgets for static content and stateful widgets to manage dynamic content or user input, both app's performance and responsiveness were optimized.
</li>
  <br>
    <li> ⚡ <b> State Management with Provider:</b> Implemented state management using the Provider package to efficiently manage and update the application state, enabling reactive UI updates when the underlying data changes. This method is essential in medium-to-large Flutter applications to handle complex states.
</li>
  <br>
      <li> ⚡ <b> Form Validation and Handling:</b> Implemented proper form input validation, ensuring that user inputs are checked for correctness before being processed. This is critical for preventing erroneous data entries and improving data integrity.
</li>
</ul>

<h2> Features </h2>

![winery-screens](https://github.com/user-attachments/assets/a7ee02fd-83ef-4e80-9fc9-13779f594a5b)

-- Filter of results based on tags

-- History of recently accessed wines

-- Fetch of items details from database

-- Editing of wines list through selection of previously inserted values

-- Creation of new data related to wines through forms, etc.

![winery-screens-2](https://github.com/user-attachments/assets/ff84827d-385b-440e-8cf8-0601cf26e600)

