A minimal (but secure) firefox that can be accessed over x2go

# Run it (and get the password)

    CID=$(docker run -p 2222:22 -t -d mini-x2go-firefox)
    docker logs $CID

# Build it

    docker build -t mini-x2go-firefox .
