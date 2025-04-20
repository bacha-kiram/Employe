# Employe
Employe of homework

package dz.univeloued.tps.classes;

public class Employe extends Personne {
    protected double salaire;

    public Employe(int id, String nom, String prenom, double salaire) {
        super(id, nom, prenom);
        this.salaire = salaire;
    }

    @Override
    public String toString() {
        return super.toString() + " mon salaire est: " + salaire + " DA";
    }
}
