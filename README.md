# Flask-Store-Backend

## Development

### Docker 
 
docker build -t rest-api-flask .   
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" rest-api-flask
