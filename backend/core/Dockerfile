# Use an official Python runtime as a parent image
FROM python:3.10

# Set the working directory in the container
WORKDIR /code

# Copy the requirements file into the container
COPY ./requirements.txt /code/requirements.txt

# Install the Python libraries
RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt

# Copy the rest of your code into the container
COPY . .

# Hugging Face STRICTLY requires the app to run on port 7860
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "7860"]