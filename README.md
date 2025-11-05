# poskus
Poskusni repozitorij

Za testiranje ideje:

* upstream repozitorij je na NIB-SI
* forked repozitorij je v ablejec
* kloniram forked direktorij v github desktop.

* commit in push gre v kloniranega
* občasno naredim merge/pull request v upstream, ki je dostopen zunanjim

## drug pristop

Izkazalo se je, da je to precej nerodno, prihaja do zmede, kam gredo spremembe po push
Drug pomembnejši razlog je, da želim videt Issues iz NIB-SI direktorija. Pri kloniranju
zahtev  ne morem neposredno urejati, kar pa postaja nujno. 

Bom preizkusil z uporabo experimentalnih branch v /develop

Imam:   
remote/glavni (default)  
remote/delovni  

1. Naredi lokalni/delovni sub-branch v lokalni/develop : lokalni/develop/delovni

2. Delaj v v lokalni/delovni
3. Commit v lokalni/delovni
4. Ponavljaj 2. - 3.
5. Merge lokalni/delovni v lokalni/develop 
6. Ponavljaj 2. - 5.   

7. Ko je treba, Push lokalni/delovni v remote/delovnai
8. Lokalno lahko zbrišeš branch lokalni/delovni in tudi remote/delovni (tick v GitHub windows)   

9. Ko je /remote/develop zrel, naredi Merge remote/delovni remote/glavni <<<< remote/delovni
10. Naredi tudi lokalnu merge Merge lokalni/glavni <<<< lokalni/delovni ali pa Fetch origin za glavni
    
11. Ko pride čas, naredi na remote Tag/Version


