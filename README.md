# mini-x2go-firefox

Minimal XFCE desktop with Firefox that can be accessed over X2Go

# Run it (and get the password)

    CID=$(docker run -p 2222:22 -t -d schreckgestalt/mini-x2go-firefox)
    docker logs $CID

# Build it

    docker build -t mini-x2go-firefox .
