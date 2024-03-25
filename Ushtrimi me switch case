#include <stdio.h>
char konvertoNoteShkronjore(int notaNumerike) {
    switch (notaNumerike) {
        case 90 ... 100:
            return 'A';
        case 80 ... 89:
            return 'B';
        case 70 ... 79:
            return 'C';
        case 60 ... 69:
            return 'D';
        default:
            return 'F';
    }
}
int main() {
    int notaNumerike; 
    printf("Jepni noten ne forme numerike: ");
    scanf("%d", &notaNumerike); 
    char notaShkronjore = konvertoNoteShkronjore(notaNumerike);
    printf("Nota me shkronje per %d eshte: %c\n", notaNumerike, notaShkronjore);
    return 0;
}
