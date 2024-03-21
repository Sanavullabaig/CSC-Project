# CSC-Project
#Project Object Detection Using AWS Services.



#	THIS CODE WORKS AS FOLLOWS:
 Imports the boto3 library for interacting with AWS services
 Analyzes a photo in an S3 bucket using AWS Rekognition and returns the number of detected labels.
 # Args:     photo (str): The name of the photo file (including extension) stored in the S3 bucket.
#Returns:
     #int: The number of labels detected in the photos 


     
 Assuming a pre-defined bucket name (replace with your actual bucket name).
 Replace with your S3 bucket name (warning: not secure).
 Creates a Rekognition client object to interact with the service.
 Calls the detect_labels method on the Rekognition client.
 Specifies the image.
 Prints a message indicating the photo being analyzed.
 Prints an empty line for better formatting.
 Iterates through each detected label in the response.
 Prints the label name.
 Prints the confidence score for the label (0.0 to 1.0).
 Prints a header for bounding box information.
 Iterates through each instance of the label.
 Prints the top coordinate of the bounding box.
 Prints the left coordinate of the bounding box.
 Prints the width of the bounding box.
 Prints the height of the bounding box.
 Prints the confidence score for the specific instance.
 Prints a header for parent labels (hierarchical classification).
 Iterates through any parent labels associated with the current label.
 Prints the name of the parent label with indentation.
 Prints a separator line for clarity.
 Prints an empty line for better formatting.
 Prints a header for parent labels (hierarchical classification).
 Iterates through any parent labels associated with the current label.
 Prints the name of the parent label with indentation.
 Prints a separator line for clarity.
 Prints an empty line for better formatting.
 Returns the total number of detected labels.
 (the length of the 'Labels' list in the response).
#MAIN
#Prompts the user for the photo name and calls the detect labels function.

