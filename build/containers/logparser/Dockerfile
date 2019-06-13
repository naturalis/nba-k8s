FROM php
MAINTAINER atze.devries@naturalis.nl

#ADD nba-log-parser /nba-log-parser
RUN apt-get update && apt-get install -y \
		  wget \
			git \
		&& rm -rf /var/lib/apt/lists/*
RUN rm -rf /nba-log-parser
RUN git clone https://github.com/naturalis/nba-log-parser /nba-log-parser
RUN cd /nba-log-parser && git pull 

