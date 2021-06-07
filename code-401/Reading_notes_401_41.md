# Location
 
 ## Get the last known location

### if you want to get the user current location you can use  Google Play services location APIs, which is usually equivalent to the last known location of the device.
_________________
## Set up Google Play services

### To access the fused location provider, your app's  must include Google Play services. we can find it  in Google Play services component via the SDK Manager and add the library to your project.


_________________________

## Specify app permissions 
### Apps whose features use location services must [request location permissions](https://developer.android.com/training/location/permissions), depending on the use cases of those features.

___________________________
## Create location services client 

### For creating location service we need to add  an instance of the Fused Location Provider Client  
____________________________
## Get the last known location


### We can now get the last known location of a user's device after we have created the Location Services client . When the  app is connected to these we can use the fused location provider's getLastLocation() 

### If we want  to request the last known location, call the getLastLocation() method.


