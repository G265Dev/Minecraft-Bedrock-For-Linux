## Install Minecraft Bedrock Launcher
```sh
sudo apt update
sudo apt install fuse
mkdir games
cd games
git clone https://github.com/G265Dev/Minecraft-Bedrock-For-Linux.git
cd Minecraft-Bedrock-For-Linux
cat Minecraft_Bedrock_Launcher-arm.0.0.617.part-* > Minecraft_Bedrock_Launcher-arm.0.0.617.AppImage
rm Minecraft_Bedrock_Launcher-arm.0.0.617.part-aa Minecraft_Bedrock_Launcher-arm.0.0.617.part-ab Minecraft_Bedrock_Launcher-arm.0.0.617.part-ac Minecraft_Bedrock_Launcher-arm.0.0.617.part-ad
chmod +x Minecraft_Bedrock_Launcher-arm.0.0.617.AppImage
```
