FROM nginx:1.16-alpine
LABEL Author="Fisayo Afolayan" app="kube-hello-world" ver="1.1"
CMD ["nginx","-g","daemon off;"]
WORKDIR /usr/share/nginx/html
COPY index.html .