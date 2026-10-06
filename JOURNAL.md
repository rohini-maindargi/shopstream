# ShopStream Build Journal

## Day 1
- Launched an Ubuntu EC2 instance (t3.medium) as my dev machine; SSH restricted to my IP.
- Installed Docker, AWS CLI, kubectl, Helm, Terraform, Node, kind and yq.
- Problem: "permission denied" on docker after adding myself to the docker group.
  Cause: group membership only applies at a new login. Fix: logged out and back in.
- Problem: two pasted commands joined into one ("no action specified").
  Lesson: check each pasted command is on its own line.
- Connected EC2 to GitHub with an SSH key and created the repo structure.
