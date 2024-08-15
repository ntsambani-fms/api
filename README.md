**GOAL: Attaining Proficiency in C# and .NET**

As part of my goal to attain proficiency in C# and .NET, I have successfully created a project using ASP.NET Core Web API .NET 8. The project involves a simple API to manage stock data, including entities such as `Stock` and `Comment`.

### Key Accomplishments:
1. **Entity Modeling**: I defined the main entities, `Stock` and `Comment`, using C# classes with proper data annotations for database mapping.
    - The `Stock` class includes properties like `Symbol`, `CompanyName`, `Purchase`, and `LastDiv`, which are essential for representing stock data.
    - The `Comment` class represents feedback or notes associated with a stock, establishing a relationship with the `Stock` class.

2. **DTOs and Mappers**: I implemented Data Transfer Objects (DTOs) to manage how data is exposed through the API.
    - Created `StockDto` and `CreateStockRequestDto` classes to separate the data model from how the API interacts with it.
    - Developed extension methods in `StockMappers` for converting between the entity models and DTOs.

3. **API Controllers**: I created a `StockController` that provides basic CRUD operations:
    - **GetAll()**: Retrieves all stocks.
    - **GetById(int id)**: Retrieves a specific stock by ID.
    - **Create(CreateStockRequestDto stockDto)**: Allows adding a new stock to the database.

  
![Screenshot 2024-08-15 105846](https://github.com/user-attachments/assets/1eca0737-7214-499d-8bac-09cae722c122)

![Screenshot 2024-08-15 105922](https://github.com/user-attachments/assets/4caefdfd-47d0-4ddb-9a24-6ab11b2bc0f0)

![Screenshot 2024-08-15 110018](https://github.com/user-attachments/assets/b34de15a-2941-4015-bb8d-e56ca51aa811)


![Screenshot 2024-08-15 110114](https://github.com/user-attachments/assets/e05ac635-424f-40cb-9997-21aad8c067af)

![Screenshot 2024-08-15 133111](https://github.com/user-attachments/assets/9bd50653-0745-48a6-ba61-b594b64b64f3)

### Next Steps:
- Continue refining the API by adding additional features such as updating and deleting stocks.
- Expand the project to incorporate more complex scenarios and learn more advanced aspects of .NET, including dependency injection, middleware, and testing.

### Reflection:
This exercise has significantly enhanced my understanding of C# and its application in building web APIs with .NET. I am on track to achieve the SMART goal I set for this year and will continue to build on this foundation.
