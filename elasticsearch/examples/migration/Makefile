PREFIX := helm-es-migration

data:
	helm upgrade --wait --timeout=900 --install --values ./data.yml $(PREFIX)-data ../../

master:
	helm upgrade --wait --timeout=900 --install --values ./master.yml $(PREFIX)-master ../../

client:
	helm upgrade --wait --timeout=900 --install --values ./client.yml $(PREFIX)-client ../../
