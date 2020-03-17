FROM alpine
RUN apk add git neovim
RUN apk add --update nodejs npm
RUN git clone https://github.com/huytd/vim-config ~/.config/nvim/
VOLUME ['~/Workspace/' '/Workspace/']
CMD /usr/bin/nvim /Workspace
