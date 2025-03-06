# Use the official Apache image
FROM httpd:alpine

# Copy all website files into Apache's default document root
COPY . /usr/local/apache2/htdocs/

# Expose port 80
EXPOSE 80

# Start Apache
CMD ["httpd-foreground"]