# Use the official Nginx image as a base
FROM nginx:alpine

# Copy the HTML file to the Nginx server's root directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# The default command to run when the container starts
CMD ["nginx", "-g", "daemon off;"]
