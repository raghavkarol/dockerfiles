FROM debian:jessie

RUN apt-get update && apt-get install -y texlive-full biber latexmk make

ENTRYPOINT ["pdflatex"]
CMD ["--help"]
