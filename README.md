# kali-vm-wifi-attack
On VMware Workstation Pro 17 boot kali linux with working "monitor mode", when your wifi-stick is connected to the virtual machine


~-Wie ihr an dem Video sehen könnt, habe ich es geschafft mit VMware Workstation Pro, eine Kali Linux Maschine zu erstellen, womit ich sogar Netzwerk angriffe voll ausführen kann/könnte-~

Tut:
Downloadet die VMware Workstation pro über den Link :
https://www.dropbox.com/scl/fi/rtsc8b1uups5qmgc3y26k/g0ttm0dus-FullVMware.rar?rlkey=gcja0dimct3z8duj2szs5s12n&dl=0

Downloadet "Kali für VMware"
Von der offiziellen seite: 
(Direkt Link)
https://cdimage.kali.org/kali-2024.2/kali-linux-2024.2-vmware-amd64.7z

1. VMware entpacken und installieren
2. Kali-vmware-amd64.7z entpacken
3. VMware ausführen, dann auf "open a virtual maschine"
4. In den Ordner "kali-vmware-amd64" und die einzige kali-vmware-amd64 datei aussuchen und öffnen die dir hier angezeigt wird
5. Starte Kali Linux
6. Schließe die W-Lan Karte an
7. Es öffnet sich ein Fenster in VMware, wo du "connect to a virtual maschine" und dann "kali-linux-vmware.." anklicken musst
8. Öffne dein Terminal sobald dein wifi-stick leuchtet und tippe ein: 
##### sudo wifite --kill
