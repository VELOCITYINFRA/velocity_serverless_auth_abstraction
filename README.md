# velocity_serverless_auth_abstraction
Velocity's managed 401 authentication  layer offloads the entire access control mechanism, providing a serverless abstraction that ensures backend immutability by requiring only a client-side integration.




> Serverless Authentication Abstraction

> The x403  client-server model typically mandates a corresponding x403  implementation on the backend
> However, Velocity has deployed a managed x401 authentication proxy layer that abstracts the entire x401 access control mechanism onto the Velocity infrastructure
> This ensures backend immutability and maintains service integrity by offloading the authentication lifecycle, requiring only a client-side integration from developers



