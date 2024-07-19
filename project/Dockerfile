# Use an official Nginx image as a base
FROM nginx:alpine

# Copy the website files to the default Nginx HTML directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]

