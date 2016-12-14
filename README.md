# VGNetworkingHelper
Its  a helper class for AFNETWORKING 3.x 
inspired by VTNetworkingHelper

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

There is also no internet connection which can be change to enable it 
Setup Reachability enable in App delegate

