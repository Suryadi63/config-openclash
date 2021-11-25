# config-openclash
 Cara pengisian akun :
 *. Masuk config editor -> proxy-provider -> balance.yaml isi dengan akun vpn kalian.
 -----------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Mengganti grup-type dari load-balance ke url-test/manual
 *. Masuk openclash -> Servers and Groups -> Proxy Groups(No Need Set when Config Create) -> klik edit di balance -> tinggal pilih di group-type dan pilih url-test/manual
 
 Url-test = otomatis mengganti ke akun dengan lattency (ping) terkecil.
 Manual = bisa ganti sendiri akun
 ------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Contoh formah akun di openclash

# TROJAN 
- name: nama akun
  type: trojan
  server: alamat host atau ip
  port: 443
  password: password-uuid
  udp: true
  sni: isibug.com
  skip-cert-verify: true
# VMESS 
- name: nama akun
  type: vmess
  server: alamat host atau ip
  port: 443
  uuid: password-uuid
  alterId: 32
  cipher: insert-cipher
  udp: true
  skip-cert-verify: true
  tls: true
  servername: isibug.com
  network: ws
  ws-path: Namassh
  ws-headers:
    Host: isibug.com
 # SHADOWSOCK
 - name: Nama akun
  type: ss
  server: alaman ip/host akun
  port: insert port
  cipher: insert cipher
  password: insert password
  udp: true
  plugin: obfs
  plugin-opts:
    mode: tls
    host: isibug.com
# SHADOWSOCKS-R
- name: nama akun
  type: ssr
  server: alamat ip/host akun
  port: port
  cipher: aes-256-cfb
  password: password-uuid
  obfs: tls1.2_ticket_auth
  protocol: auth_sha1_v4
  obfs-param: obfs=tls;obfs-host=bug.com
  udp: true