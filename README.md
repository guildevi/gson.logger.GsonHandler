# gson.logger.GsonHandler
gson.logger.GsonHandler is java.utils.logging.Handler forwarding log records to a static method. 
To be used with Whisk Action and returns logs in the Json response object. 

OpenWhisk Java action is a Java program with a method called main that has the exact signature as follows:
public static com.google.gson.JsonObject main(com.google.gson.JsonObject);
(https://github.com/apache/openwhisk/blob/master/docs/actions-java.md)
