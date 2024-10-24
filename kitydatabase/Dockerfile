# Use the official MongoDB image from Docker Hub
FROM mongo:latest

# Set environment variables
ENV MONGO_INITDB_ROOT_USERNAME=root
ENV MONGO_INITDB_ROOT_PASSWORD=123456

# Expose MongoDB port
EXPOSE 27017

# Optionally, set a volume for MongoDB data
VOLUME /data/db

# Start MongoDB service
CMD ["mongod"]
