FROM circleci/ruby

RUN sudo apt-get update && sudo apt-get upgrade -y
RUN sudo apt-get install -y libpcap-dev

RUN sudo gem install miam
RUN sudo gem install roadworker