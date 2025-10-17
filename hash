echo '28cc09d8d8959871a97b24a07d87bcb05b9f3e7ac6d9f20ff82196ca5f908b2c' > ~/single_keccak.txt                                                                                                                                          
hashcat -m 17800 -a 0 ~/single_keccak.txt /usr/share/wordlists/rockyou.txt -o ~/cracked_keccak.txt  
cat ~/cracked_keccak.txt                                                                                                                                                                                                               
hashcat -m 17800 --show ~/single_keccak.txt   
python3 -m venv venv                                                                                                                                                                                                                   
pip install pycryptodome                                                                                                                                                                                                               
#Validasi apakah outputnya sesuai dengan kode hash yang diberikan 
python3 - <<'PY'                                                                                                                                                                                                                       
from Crypto.Hash import keccak
pw = b"Password"
h = keccak.new(digest_bits=256)
h.update(pw)
print(h.hexdigest())
PY
