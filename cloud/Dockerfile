FROM python:alpine

WORKDIR /application

COPY requirements.txt .

COPY random_paragraphs.txt .


RUN pip install -r nltk.txt

COPY count_word.py .

CMD python count_word.py