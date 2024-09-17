### Lab: Start AutoGen Studio

Install `autogenstudio` in the terminal by running following commands in the terminal: 

```
# Download the get-pip.py script
curl -O https://bootstrap.pypa.io/get-pip.py

# Install pip using the get-pip.py script with Python 3.11
python3.11 get-pip.py

# Verify pip version
python3.11 -m pip --version

# Install distutils for Python 3.11
sudo apt install -y python3.11-distutils

pip install autogenstudio
```

Autogen will require an API Key. We will use OpenAI so execute this command on the command line:

`export OPENAI_API_KEY="your-key-here"`

To run AutoGen Studio, you need to specify the port it will operate on, using the following command:

`sudo OPENAI_API_KEY="your-key-here" autogenstudio ui --port 8081 --host 0.0.0.0 &`

This command configures AutoGen Studio to run on port 8081 and be accessible from any machine.

Note: to run this in the background so it doesn’t end when the terminal ends, use this command:

`sudo OPENAI_API_KEY="your-key-here" nohup autogenstudio ui --port 8081 --host 0.0.0.0 &`

#### Access AutoGen Studio

Open your web browser and go to `http://<your-instance-dns-ip>:8081/`. You should now see the AutoGen Studio interface.
