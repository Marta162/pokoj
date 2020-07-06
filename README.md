# pokoj
print('podaj długość swojego pokoju w centymetrach')
dl=float(input())/100

print('podaj szerokość swojego pokoju w centymetrach')
sze=float(input())/100

print('długość twojego pokoju to {:.2f}m a szerokość to {:.2f}m'.format(dl,sze))
pow=sze*dl
print('powierzchnia pokoju wynosi{:.2f}m^2'.format(pow))

print('Wolisz operować na calach niz na metrach?? Podaj T/N')
decyzja=input()
if decyzja =='T':
    dlcal=dl*39.370
    szecal=sze*39.370
    print('długość twojego pokoju to {:.2f}cala a szerokość to {:.2f}cala'.format(dlcal,szecal))
    powcal=szecal*dlcal
    print('powierzchnia pokoju wynosi{:.2f}cal^2'.format(powcal))

else:
    print('Nie to nie :)')
