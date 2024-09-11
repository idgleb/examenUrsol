examen1 Ursol

crea diagrama de clase

https://lucid.app/lucidchart/8f6ed411-3802-4bbf-b58b-d891c9a71941/edit?invitationId=inv_c6602576-eef6-4512-aaf5-70ded557bb15

    public static boolean isNumeroDe_1_10(String str) {
        if (str.isEmpty()) {
            return false;
        } else {
            for (int i = 0; i < str.length(); i++) {
                if (str.charAt(i) < '0' || str.charAt(i) > '9') return false;
            }
            int mes = Integer.parseInt(str);
            if (mes < 1 || mes > 10) {
                return false;
            }
        }
        return true;
    }