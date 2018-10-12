FROM buildpack-deps:jessie

RUN echo 'deb http://apt.llvm.org/jessie/ llvm-toolchain-jessie-3.6 main' >> /etc/apt/sources.list \
    && wget -O - http://apt.llvm.org/llvm-snapshot.gpg.key | apt-key add - \
    && apt-get update \
    && apt-get install -y clang-3.6 

