# Use the official Ubuntu image
FROM ubuntu:latest
 
# Update package lists and install Apache
RUN apt-get update && \
    apt-get install -y apache2
 
# Expose port 80
EXPOSE 80
 
# Start Apache in the foreground
CMD ["apache2ctl", "-D", "FOREGROUND"]
