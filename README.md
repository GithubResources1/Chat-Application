# Chat Application54321

- ## Frameworks and Language used
  - #### Spring Boot Framework
  - #### Java language
- ## Data Flow
  - ### UserController
     - ##### _createUser( )_   
     - ##### _validateUserRequest( )_       
     - ##### _setUser( )_     
     - ##### _getUsers( )_  
     - ##### _login( )_  
     - ##### _validateLogin( )_  
     - ##### _updateUser( )_
     - ##### _deleteUser( )_
     
  - ### StatusController
     - ##### _createStatus( )_   
     - ##### _setStatus( )_         
    
  - ### ChatHistoryController
     - ##### _saveMessage( )_   
     - ##### _validateRequest( )_ 
     - ##### _setChatHistory( )_ 
     - ##### _getChatsByUserId( )_ 
     - ##### _getConversationBetweenTwoUsers( )_ 

   - ### UserService
     - ##### _saveUser( )_  
     - ##### _getUsers( )_ 
     - ##### _login ( )_ 
     - ##### _createResponse( )_ 
     - ##### _deleteUserByUserId( )_ 
     - ##### _updateUser( )_
    
   - ### StatusService
     - ##### _saveStatus( )_   
   
   - ### ChatHistoryService
     - ##### _saveMessage( )_
     - ##### _getChatsByUserId( )_
     - ##### _getConversation( )_
     
   - ### UserRepository
     - ##### _findByUsername( )_
     - ##### _getUserByUserId( )_
     - ##### _getAllUsers( )_
     - ##### _deleteUserByUserId( )_
     - ##### _save( )_
   
   - ### StatusRepository
     - ##### _save( )_
     
   - ### ChatHistoryRepository
     - ##### _getChatsByUserId( )_
     - ##### _getConversation( )_
     - ##### _save( )_
    
   - ### CommonUtils
     - ##### _isValidPassword( )_
     - ##### _isValidEmail( )_
     - ##### _isValidPhoneNumber( )_
     

- ## Database Used
  - #### MySQL Database : chat_application_db
  
- ## Project Summary
  In thismodified project we have created 2 models namely;User, ChatHistory and Status. We have provided some endpoints and also in this section below we have given our API. Using this API we can perform the CRUD operations accordingly.
  
  End Points:
    - ##### /status   
   
    - ##### /user/create-user  

    - ##### /user/get-users

    - ##### /user/login  
    
    - ##### /user/update-user/{userId}
   
    - ##### /user/delete-user/{userId}

    - ##### /chat/send-message

    - ##### /chat/get-chat 
    
    - ##### /chat/get-conversation 
