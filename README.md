# GaiaNet-Node
### Follow these steps for smooth installation of the GaiaNet Node. This will help you avoid some of the most common mistakes when installing.

### Step 1: Update Your System

```bash
sudo apt update
```

### Step 2: Install Required Libraries

```bash
sudo apt-get install libgomp1
```

### Step 3: Download and Run the Installation Script

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

### Step 4: Source Your Bash Configuration

```bash
source ~/.bashrc 
```

### Step 5: Initialize GaiaNet with Configuration

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```

### Step 6: Start GaiaNet

```bash
gaianet start
```

### By following these steps, you should be able to install and run GaiaNet Node without running into any errors. Enjoy using GaiaNet for your AI projects!
