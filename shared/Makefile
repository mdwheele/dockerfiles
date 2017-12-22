.PHONY: xmind

image:
	docker build -t $(TAG) .

push:
	docker push $(TAG)

shell:
	docker run -it --rm $(TAG) bash
