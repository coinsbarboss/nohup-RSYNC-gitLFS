Creating encrypted archive
`tar czvpf - FILES | gpg --symmetric --cipher-algo aes256 -o FILES.tar.gz.gpg`
# |
Extracting encrypted archive 
`gpg -d FILES.tar.gz.gpg | tar xzvf -`

# |

Scripts survive terminal closure
# nohup ./script.sh &

# |

# rsync -azP -e "ssh -p PORT_NUMBER" source destination
# |

# GIT_LFS_INSTALL
`curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | bash`

`apt-get install git-lfs`

