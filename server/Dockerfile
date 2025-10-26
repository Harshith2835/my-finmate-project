#Use an official Node.js runtime as a parent image
FROM node:18 [cite: 585]

#Set the working directory to /app
WORKDIR /app [cite: 585]

# Copy package.json and package-lock.json to the container
COPY package*.json ./ [cite: 585]

#Install dependencies
RUN npm install [cite: 585]

# Copy the current directory contents into the container at /app
COPY . . [cite: 585]

#Make port 4000 available to the world outside this container
EXPOSE 4000 [cite: 585]

# Define the command to start the application
CMD ["node", "index.js"] [cite: 585]