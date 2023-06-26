podman build -t dockeragent:latest .

azp_url=https://dev.azure.com/carlosxpk/
azp_token=we22gy34szarmi3p3vyqwon6jkajg3pgpve7nyq2dqvje55k2eyq
azp_agent_name=carlosxpk

docker run -e AZP_URL=$azp_url -e AZP_TOKEN=$azp_token -e AZP_AGENT_NAME=$azp_agent_name dockeragent:latest

