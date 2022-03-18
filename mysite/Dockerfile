FROM django:onbuild

RUN useradd -u 1000 -g 100 -d /home/app app

RUN apt-get install -y python-dev python-pip python-setuptools

RUN apt-get install -y libtiff-dev libjpeg-dev zlib1g-dev \
    libfreetype6-dev liblcms2-dev libwebp-dev \
    --no-install-recommends && rm -rf /var/lib/apt/lists/*

