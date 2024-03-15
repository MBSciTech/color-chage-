public class colorChange {
    static final String white = "\u001B[0m";
    static final String red = "\u001B[31m";
    static final String green = "\u001B[32m";
    static final String yellow = "\u001B[33m";
    static final String blue = "\u001B[34m";
    static final String Magenta = "\u001B[35m";
    static final String cyan = "\u001B[36m";
    // background color
    static final String black = "\u001B[40m";
    static final String darkRed = "\u001B[41m";
    static final String darkGreen = "\u001B[42m";
    static final String darkYellow = "\u001B[43m";
    static final String darkBlue = "\u001B[44m";
    static final String darkMagenta = "\u001B[45m";
    static final String darkCyan = "\u001B[46m";
    // text style
    static final String bold = "\u001B[1m";
    static final String underline = "\u001B[4m";
    static final String blink = "\u001B[5m";
    static final String inverse = "\u001B[7m";
    static final String hidden = "\u001B[8m";
    static final String normal = "\u001B[22m";

    public static void main(String[] args) {
        System.out.println(red + "this text is red");
        System.out.println(green + "this text is green");
        System.out.println(yellow + "this text is yellow");
        System.out.println(blue + "this text is blue");
        System.out.println(Magenta + "this text is magenta");
        System.out.println(cyan + "this text is cyan" + white);
        System.out.println();
        // System.out.println(bold + "this text is bold" + normal);
        // System.out.println(underline + "this text is underline" + normal);
        // System.out.println(blink + "this text is blink" + normal);
        // System.out.println(inverse + "this text is inverse" + normal);
        // System.out.println(hidden + "this text is hidden" + normal);
        System.out.println();
        System.out.println(black + "this text is black" + black);
        System.out.println(darkRed + "this text is dark red" + black);
        System.out.println(darkGreen + "this text is dark green" + black);
        System.out.println(darkYellow + "this text is dark yellow" + black);
        System.out.println(darkBlue + "this text is dark blue" + blac);
        System.out.println(darkMagenta + "this text is dark magenta" + black);
        System.out.println(darkCyan + "this text is dark cyan" + black);
        System.out.println();

    }
}
