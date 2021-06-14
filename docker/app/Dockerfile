FROM rust

WORKDIR app
COPY ./app .

RUN cargo install cargo-watch

CMD ["cargo", "watch", "--exec", "run"]
