# Todays Task: Secrets and ConfigMaps

- Create a secret1.yaml. The yaml should create a secret called secret1 and store password:12345678. Create that secret.
- Create a pod1.yaml which creates a single pod of image bash . This pod should mount the secret1 to /tmp/secret1. This pod should stay idle after boot. Create that pod.
- Confirm pod1 has access to our password via file system.
- On your local create a folder drinks and its content: mkdir drinks; echo ipa > drinks/beer; echo red > drinks/wine; echo sparkling > drinks/water
- Create a ConfigMap containing all files of folder drinks and their content.
- Make these ConfigMaps available in our pod1 using environment variables.
- Check on pod1 if those environment variables are available.
