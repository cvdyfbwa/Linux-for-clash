# Linux-for-clash


> cd Linux for clash
>
> sudo su
>
> vim .env      // The value of the variable CLASH_URL is changed to the subscription link of ClashX
>
> ./start.sh     //Start service
>
> source /etc/profile.d/clash.sh
>
> proxy_on     //Enable system proxy
>
> netstat -tln | grep -E '9090|789'
>
> env | grep -E 'http_proxy|https_proxy'
>
> sh shutdown.sh      //Close service
>
> unset http_proxy
>
> unset https_proxy


Linux for clash configuration tutorial
