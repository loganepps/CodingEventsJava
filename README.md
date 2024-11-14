The Person class should hold the following fields:
  1. id (int) - the unique user ID
  2. firstName (String) - the user's first name
  3. lastName(String) - the user's last name
  4. email (String) - the user's email, which will also function as their username
  5. password (String) - the user's password
* This class needs getters and setters for all fields except id, which will ONLY have a getter (since it should remain unchanged).

The Person class may also include the following references:
  1. PersonProfile - a class to gather up all of the profile information about a user
  2. List<Events> eventsAttending - to store events the user wants to attend
  3. List<Events> eventsOwned - a different list for storing events created by the user

Person would have a many-to-many relationship with Event via List<Events> eventsAttending, 
  and would have a one-to-many relationship with Event via List<Events> eventsOwned
