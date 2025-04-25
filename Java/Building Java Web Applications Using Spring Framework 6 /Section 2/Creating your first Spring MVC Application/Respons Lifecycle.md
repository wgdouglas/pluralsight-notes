# Request/Response Lifecycle

---

- Your `Displatcher Servlet` inside of Spring is the Incoming request that comes to your Servlet Front Controller
  - This will delegate your request to one of the controllers you created with Spring
  - The `Dispatcher` is the router that dictates what controller will handle the request while the chosen controller will route traffic to where it needs to go 
    - It also handles the request to be handed over to the back end
