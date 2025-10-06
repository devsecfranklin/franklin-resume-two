# franklin-resume-two

[![DOI](https://zenodo.org/badge/407849291.svg)](https://zenodo.org/badge/latestdoi/407849291) [![Go Report Card
](https://goreportcard.com/badge/github.com/golang-standards/project-layout?style=flat-square)](https://goreport
card.com/report/github.com/golang-standards/project-layout)

## Golang

```sh
go mod init github.com/devsecfranklin/franklin-resume-two
go mod tidy # create/update go.mod
go mod verify # create go.sum
go run cmd/main.go # run the application on port 8080
```

## Certbot

```sh
sudo apt -y install certbot python3-certbot-nginx
sudo certbot --nginx -d XYZ.bitsmasher.net
certbot certificates # displays information about the certificates that Certbot has obtained
systemctl status certbot.timer # showing whether it’s active and when it’s scheduled to run next.
certbot renew --dry-run # If dry run is successful, the auto-renewal has been set up correctly.
```