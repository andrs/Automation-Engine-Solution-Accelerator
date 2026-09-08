

curl -Lo bicep https://github.com/Azure/bicep/releases/latest/download/bicep-linux-musl-x64
chmod +x ./bicep
sudo mv ./bicep /usr/local/bin/bicep
mkdir -p ~/.azure/bin
cp /usr/local/bin/bicep ~/.azure/bin/bicep
