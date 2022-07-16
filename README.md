1. create folder rsvp and ingress

        mkdir rsvp
        mkdir ingress
        
2. add 4 file yaml in rsvp directory

        cd rsvp
        vi <nama>.yaml

3. add 2 file yaml in ingress directory

        cd ingress
        vi <nama>.yaml

4. run the file yaml 

        kubectl apply -f rsvp/<name>.yaml
        kubectl apply -f ingress/<name>.yaml

