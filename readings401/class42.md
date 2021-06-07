# Locations

- Using the Google Play services location APIs, your app can request the last known location of the user's device.


## Set up Google Play services
- To access the fused location provider, your app's development project must include Google Play services.
-  Download and install the Google Play services component via the SDK Manager and add the library to your project.

## Specify app permissions
- Apps whose features use location services must request location permissions, depending on the use cases of those features.

## Create location services client
- In your activity's onCreate() method, create an instance of the Fused Location Provider Client 

## Get the last known location
- Once you have created the Location Services client you can get the last known location of a user's device. When your app is connected to these you can use the fused location provider's getLastLocation() method to retrieve the device location.

