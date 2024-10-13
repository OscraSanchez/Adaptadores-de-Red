# Que sabemos de los Adaptadores de Red de VirtualBox

En VirtualBox, los adaptadores de red permiten configurar cómo las máquinas virtuales se conectan a la red y se comunican con otros dispositivos. Existen barios tipos de Adaptadores:

1. NAT (Network Address Translation): Permite que la máquina virtual acceda a Internet a través del host, pero no permite la comunicación directa con otras máquinas virtuales o dispositivos en la red local.

<img src="https://github.com/OscraSanchez/Adaptadores-de-Red/blob/main/nat.png" width="300" height="250">

2. Adaptador en Puente (Bridged Adapter): Conecta la máquina virtual directamente a la red física del host, permitiendo que la máquina virtual obtenga una dirección IP de la misma red que el host y se comunique con otros dispositivos en esa red.

<img src="https://github.com/OscraSanchez/Adaptadores-de-Red/blob/main/puente.png" width="350" height="250">

3. Red Interna (Internal Network): Crea una red aislada entre las máquinas virtuales, sin acceso a Internet ni al host.

<img src="https://github.com/OscraSanchez/Adaptadores-de-Red/blob/main/interna.png" width="300" height="250">

4. Solo Anfitrión (Host-Only Adapter): Permite la comunicación entre la máquina virtual y el host, pero no con otros dispositivos en la red ni con Internet.

<img src="https://github.com/OscraSanchez/Adaptadores-de-Red/blob/main/Host.png" width="300" height="250">

5. Red NAT (NAT Network): Como el NAT, pero permite la comunicación entre múltiples máquinas virtuales en la misma red virtual.

<img src="https://github.com/OscraSanchez/Adaptadores-de-Red/blob/main/rednat.png" width="300" height="250">
