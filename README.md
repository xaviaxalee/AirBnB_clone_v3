AirBnB_clone_v3 Project

1. **Update the Repository and README:**
   - Fork the existing codebase to a new repository named "AirBnB_clone_v3."
   - Update the README.md file with the following changes:
     - Add yourself as an author of the project.
     - Provide new information about your contribution.
     - Make any necessary improvements to the README.

2. **Never Fail!**
   - Ensure that all current tests pass. Do not delete existing tests.
   - Add new tests where applicable.
   - Confirm the success of tests using the provided command:
     ```bash
     python3 -m unittest discover tests
     ```

3. **Improve Storage**
   - Create a branch named "storage_get_count."
   - Update `DBStorage` and `FileStorage` classes with two new methods:
     - `get(self, cls, id)`: Retrieve one object based on class and ID.
     - `count(self, cls=None)`: Count the number of objects in storage matching the given class.
   - Add new tests for these methods in each storage engine.

4. **Status of your API**
   - Create a new API endpoint to return the status of your API.
   - Set up the API with the following steps:
     - Create a folder named "api" at the root with an empty `__init__.py` file.
     - Inside the "api" folder, create a subfolder named "v1" with an empty `__init__.py` file.
     - Inside "v1," create a file named `app.py` with necessary configurations.
     - Create a folder named "views" inside "v1" and an empty `__init__.py` file.
     - Create a file named `index.py` inside "views" to handle the status endpoint.

5. **Some Stats?**
   - Create an endpoint that retrieves the number of objects by type.
   - Implement the route `/api/v1/stats` to return a JSON with counts for each object type.

6. **Not Found**
   - Create a JSON-formatted 404 response for the 404 error.
   - Handle 404 errors in `api/v1/app.py` and return the JSON: `"error": "Not found"`.

7. **State**
   - Create a new view for State objects that handles default RESTFul API actions.
   - Implement routes for listing all states, retrieving a state by ID, deleting a state, creating a state, and updating a state.

8. **City**
   - Create a new view for City objects following the same pattern as the State view.
   - Implement routes for listing all cities of a state, retrieving a city by ID, deleting a city, creating a city, and updating a city.

9. **Amenity**
   - Create a new view for Amenity objects following the same pattern as the State and City views.
   - Implement routes for listing all amenities, retrieving an amenity by ID, deleting an amenity, creating an amenity, and updating an amenity.

Make sure to follow the specified file organization, coding standards (PEP 8), and provide comprehensive documentation for modules, classes, and functions. Don't forget to create and run tests for each new functionality. After completing each task, submit a pull request on GitHub and ask for a peer review.
