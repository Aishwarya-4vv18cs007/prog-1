import java.util.*;
import java.math.BigInteger;
import java.lang.*;
class ed {
public static void main(String[] args) {
BigInteger pubKey = new BigInteger(args[0]);
 BigInteger prvKey = new BigInteger(args[1]);
BigInteger n = new BigInteger(args[2]);
 int asciiVal = Integer.parseInt(args[3]);
 BigInteger val = new BigInteger(""+ asciiVal);
 BigInteger cKey = val.modPow(pubKey,n);
System.out.println("Cipher Text: " + cKey);
BigInteger pVal = cKey.modPow(prvKey,n);
int Pval = pVal.intValue();
System.out.println("Plain text: " + Pval);
}
}
