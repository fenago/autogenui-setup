# AutoGen Studio

AutoGen Studio is an AutoGen-powered AI app (user interface) to help you rapidly prototype AI agents, enhance them with skills, compose them into workflows and interact with them to accomplish tasks. It is built on top of the `AutoGen` framework, which is a toolkit for building AI agents.

### Signup Github

Open `https://github.com/signup` in the brwoser and signup if you don't have the account already.

2. Create `New Repository` and name it autogenui.

![](./images/repo.png)

### Signup GitPod
1. Open `https://gitpod.io/` in the browser and login with github.

2. Click `New Workspace` and select the github repo.

![](./images/0.png)

Make sure the select following and click **Continue**:

![](./images/1.png)

![](./images/2.png)

### Set OpenAI Key

Running following command in the terminal:

`export OPENAI_API_KEY=ADD_HERE`

**Note:** You can get the above key from instructor.

### Installation

**Install from PyPi**

With Python 3.10 or newer active in your virtual environment, use pip to install AutoGen Studio:

```bash
pip install autogenstudio
```

![](./images/3.png)

### Running the Application

Once installed, run the web UI by entering the following in your terminal:

```bash
autogenstudio ui --port 8081
```

![](./images/4.png)


This will start the application on the specified port. Open your web browser and go to `http://8081-GITPOD_URL/` to begin using AutoGen Studio. You can get the complete URL from **PORTS** tab.

![](./images/5.png)

![](./images/6.png)

Now that you have AutoGen Studio installed and running, you are ready to explore its capabilities, including defining and modifying agent workflows, interacting with agents and sessions, and expanding agent skills.
