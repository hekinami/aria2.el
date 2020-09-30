# aria2.el
Emacs interface for aria2

The original one have some problems when we try to work with multibyte filenames/links and it tries to start a aria2 rpc server itself which is not necessary if we prefer start a rpc server (local or remote) ourselves (for example with systemd)

I just tried fixing the issues above. I didn't cover all aspects and it's enough for me for now.
