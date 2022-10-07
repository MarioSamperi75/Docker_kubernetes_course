FROM python

WORKDIR /app
# we just copy package.json before installing
# if you change juste the code, the build process will use a cached npm install
# faster, no need to install the package again unnecessarly 

COPY . /app

CMD ["python", "rng.py"]
