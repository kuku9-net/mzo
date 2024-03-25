git add . && git commit -m "$(date -Iseconds -r $(latest.sh ))" && GIT_SSH_COMMAND="ssh -i ~/.ssh/id_ed25519_kuku9" git push origin main


