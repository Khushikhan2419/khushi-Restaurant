# Use the official Nginx base image
FROM nginx:alpine

# Remove the default nginx static files
RUN rm -rf /usr/share/nginx/html/*

# Copy your index.html to the nginx html directory
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
