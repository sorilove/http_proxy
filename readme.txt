설정
npm config set proxy http://127.0.0.1:8888 && npm config set https-proxy http://127.0.0.1:8888 && npm config set static-ssl false

해제
npm config rm proxy && npm config rm https-proxy && npm config delete proxy && npm config delete https-proxy





npm cache verify
npm cache clean --force
npm install --cache /tmp/empty-cache






[proxy 설정]
export https_proxy=http://222.122.191.145:8080 && export http_proxy=http://222.122.191.145:8080

[proxy 초기화]
export https_proxy= && export http_proxy=