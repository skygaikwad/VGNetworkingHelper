# VGNetworkingHelper
Its  a helper class for AFNETWORKING 3.x 
inspired by VTNetworkingHelper

- Serialization JSON
- Authentication Option
- Custom HTTP Body

Implementation and Using  

/////////////////////////////////

    [[VGAFNetworkingHelper sharedInstance]performRequestWithPath:requestURL withAuth:NO forMethod:@"GET" withRequestJSONSerialized:NO withParams:parameters withCompletionHandler:^(VGAFNetworkingResponse *response){
       if (response.isSuccessful) {
       // Do some stuff
       else
    {
      // failed do some suffs
    }}];

////////////////////////////

There is also no internet connection action which can be change but need to enable it 
Setup Reachability enable in App delegate


Feel Free to modify.

Download Zip 
