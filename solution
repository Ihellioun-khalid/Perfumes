/*********************************************
 * OPL 12.6.0.0 Model
 * Perfumes
 *********************************************/

//Make sure you use c[i] to access the i-th cost 
//and do not remove/change the following line
float c[1..2] = [300, 500];

dvar float x;
dvar float y;
maximize c[1]*x+c[2]*y;


subject to {
      x        <=4;
        2*y    <=12;
    3*x+2*y    <=18;
    x>=0;
    y>=0;
}

/* Affichage de la solution */
execute {
  writeln("Post-traitement: ");
  writeln("La valeur de l'objectif est de "+cplex.getObjValue());
} 