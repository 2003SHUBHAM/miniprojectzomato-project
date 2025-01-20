# Use the official Nginx image as the base for serving HTML and CSS
FROM nginx:alpine AS final

# Set the working directory to the default Nginx directory
WORKDIR /usr/share/nginx/html

# Copy your HTML, CSS, and other static files into the container
COPY . .

# Expose port 80 for HTTP traffic
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]