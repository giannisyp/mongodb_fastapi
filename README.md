# MongoDB with FastAPI

This is a small sample project demonstrating how to build an API with [MongoDB](https://developer.mongodb.com/) and [FastAPI](https://fastapi.tiangolo.com/).

pip install -r requirements.txt

# Add the MONGODB_URL connection enviroment variable to your system

client = motor.motor_asyncio.AsyncIOMotorClient(os.environ["MONGODB_URL"])

# Start the service:

uvicorn app:app --reload
