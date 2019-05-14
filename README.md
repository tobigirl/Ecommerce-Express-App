### Task fot the week.
Build APIs for an E-commerce app. The user of the app should be able o sign up, login, go to homepage and be greeted with a welcome message, get email notification when they register. User should be able to log out, post images, update their profile, delete an image and any other functionality you can think of.

### Available Endpoints
* **"/signup"** : Method **POST**. This is the endpoint for user to register 
	* Request Object:
		* firstName: Type(String)
		* lastName: Type(String)
		* username: Type(String) 
		* password: Type(String) 
		* bio: Type(String)
		* email: Type(String)
		* gender: Type(String)
		* phoneNumber: Type(String)
		* address: Type(String)
		* state: Type(String) 
	* Response Object:
		* firstName: Type(String)
		* lastName: Type(String)
		* username: Type(String) 
		* password: Type(String) 
		* bio: Type(String)
		* email: Type(String)
		* gender: Type(String)
		* phoneNumber: Type(String)
		* address: Type(String)
		* state: Type(String) 



* **"/login"** : Method **POST**. This is the endpoint for login into the app
	* **Request Object**:
		* username: Type(String)
		* password: Type(String)
	* **Response Object**:
		* username: Type(String)
		* password: Type(String)


* **"/task"** : Method **POST**. This is the endpoint for user to input a task.
	* **Request Object**:
		* taskName: Type(String)
		* time: Type(String)
		* description: Type(String)
		* isCompleted: Type(Boolean)
		* reminderTime: Type(String)
	* **Response Object**:
		* username: Type(String)
		* password: Type(String)