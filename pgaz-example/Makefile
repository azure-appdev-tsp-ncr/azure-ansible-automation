dev:
	docker build -t pgaz-example .
	docker run -it --rm pgaz-example \
		ansible-playbook work/deploy.yml --extra-vars "environ=dev"
prod:
	docker build -t pgaz-example .
	docker run -it --rm pgaz-example \
		ansible-playbook work/deploy.yml --extra-vars "environ=prod"
shell:
	docker build -t pgaz-example .
	docker run -it --rm pgaz-example \
	sh \
