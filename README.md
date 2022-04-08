# Act-10
Avance de poker

Public class Baraja {
    private String baraja;
    private String elige;
    private String mano;

    public void baraja(String baraja, String elige, String mano) {
        this.baraja = baraja;
        this.elige = elige;
        this.mano = mano;
    }

    public String getbaraja() {
        return baraja;
    }

    public void setBaraja(String baraja) {
        this.baraja = baraja;
    }

    public String getelige() {
        return elige;
    }

    public void setColor(String elige) {
        this.elige = elige;
    }

    public String getmano() {
        return mano;
    }

    public void setmano(String mano) {
        this.mano = mano;
    }
}
