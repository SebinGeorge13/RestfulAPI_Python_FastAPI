# RestfulAPI_Python_FastAPI
This project shows how to use a **Kafka Consumer** inside a Python Web API built using  **FastAPI**. This can be very useful for use cases where one is building a Web API that  needs to have some state, and that the state is updated by receiving a message from a  message broker (in this case Kafka).

## Technologies

The implementation was done in `python>=3.7` using the web framework `fastapi`, and for 
interacting with **Kafka** the `aiokafka` library was chosen. The latter fits very well
within an `async` framework like `fastapi` is.
