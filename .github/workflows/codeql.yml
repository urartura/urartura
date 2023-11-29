import java.util.Random;

class Rennstrecke {
        int gesamtstrecke;

        Rennstrecke(int gesamtstrecke) {
            this.gesamtstrecke = gesamtstrecke;
        }
    }

class Schnecke {
        String name;
        int position = 0;

        Schnecke(String name) {
            this.name = name;
        }
    }

    void main() {
        new SchneckenRennen().hauptprogramm();
    }
}
    
class SchneckenRennen extends Hamster {
    
    void hauptprogramm() {
        Schnecke[] schnecken = {
            new Schnecke("Schnecke 1"),
            new Schnecke("Schnecke 2"),
            new Schnecke("Schnecke 3"),
            new Schnecke("Schnecke 4"),
            new Schnecke("Schnecke 5"),
            new Schnecke("Schnecke 6")
        };

        Rennstrecke rennstrecke = new Rennstrecke(8);

        for (int i = 0; i < schnecken.length; i++)
        {
        spielen (schnecken[i]
     }

    void spielen(Schnecke schnecke, Rennstrecke rennstrecke) {
        Random generator = new Random();

		for (Schnecke schnecke : schnecken){
            int schritte = generator.nextInt (6) + 1; // es soll eine zahl zwischen 1 und 6 generiert werden
            for (int i = 0; i < schritte; i++)
            {
            vor();
            }

            if (kornDa()) {
                System.out.println(schnecke.name + " hat gewonnen! Korn am Ende des Spiels.");
                return;
            }

            System.out.println(schnecke.name + " hat " + schritte + " Schritte vorwärts gemacht. ");

            if (hatGewonnen(schnecke, rennstrecke.gesamtstrecke)) {
                System.out.println(schnecke.name + " hat die Rennstrecke erreicht und gewonnen!");
                return;
            }
        }

        System.out.println("Spiel beendet. " + schnecke.name + " hat gewonnen.");
    }

    boolean hatGewonnen(Schnecke schnecke, int gesamtstrecke) {
        return schnecke.position >= gesamtstrecke;
    }
}
