#include <iostream>
#include <string>

using namespace std;

void afficherAccueil() {
    cout << "=========================================\n";
    cout << "          BIENVENUE SUR PORNHESS         \n";
    cout << "   Le seul site réservé aux MINEURS 😂   \n";
    cout << "=========================================\n\n";

    cout << "⚠️  Ce site a été saisi par la Brigade du Goût Moral ⚠️\n";
    cout << "  Toute tentative d'accès est inutile...\n\n";

    cout << "Souhaitez-vous continuer ?\n";
    cout << "1 - Oui, je suis MINEUR\n";
    cout << "2 - Non, je suis MAJEUR (et trop vieux pour ces bêtises)\n";
    cout << "> ";
}

void redirectionMineur() {
    cout << "\n✅ Accès autorisé. Bienvenue, jeune rebelle.\n";
    cout << "Voici les stars du jour :\n";
    cout << "- Laxie Lawless\n";
    cout << "- Tifa Censure\n";
    cout << "- Brigitte La Foudre\n\n";
    cout << "🐱 Bonus : image ASCII d’un chat censuré\n\n";
    cout << R"( 
        /\_/\  
       ( o.o ) < censuré
        > ^ < 
    )" << endl;
}

void refuserMajeur() {
    cout << "\n🚫 Accès refusé. Va payer tes impôts.\n";
    cout << "Tu as dépassé l'âge légal de l'amusement absurde.\n";
}

int main() {
    int choix;

    afficherAccueil();
    cin >> choix;

    if (choix == 1) {
        redirectionMineur();
    } else if (choix == 2) {
        refuserMajeur();
    } else {
        cout << "\nCommande non reconnue. Retourne jouer aux échecs.\n";
    }

    cout << "\nMerci d'avoir visité Pornhess™. Site 100% sans contenu.\n";
    return 0;
}
