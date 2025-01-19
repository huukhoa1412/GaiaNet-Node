# GaiaNet-Node
### Follow these steps for smooth installation of the GaiaNet Node. This will help you avoid some of the most common mistakes when installing.

### Step 1: Create your Gaia Account [here](https://gaianet.ai/reward?invite_code=RSh26G) and complete all quests.

### Step 2: Update Your System

```bash
sudo apt update
```

### Step 3: Install Required Libraries

```bash
sudo apt-get install libgomp1
```

### Step 4: Download and Run the Installation Script

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

### Step 5: Source Your Bash Configuration

```bash
source ~/.bashrc 
```

### Step 6: Initialize GaiaNet with Configuration

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```

### Step 7: Start the Node

```bash
gaianet start
```

### Run the command below to get your ```Node ID``` and your ```Device ID```. You need both so you can bind your NODE with your ```Gaia Account```

```bash
gaianet info
```

### By following these steps, you should be able to install and run GaiaNet Node without running into any errors. Enjoy using GaiaNet for your AI projects!
