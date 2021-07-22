# Generate a new Keystore
keytool -genkey -v -keystore foobar.keystore -alias foobar -keyalg RSA -keysize 2048 -validity 10000

# Build apps
# ns build android --release \
#  --key-store-path ./keystore \
#  --key-store-password 12345678 \
#  --key-store-alias RSVG \
#  --key-store-alias-password RSVG
