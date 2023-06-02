### You need add A panel and goto coustom code and change like:
`jPanel1 = new javax.swing.JPane1(); `<br/>
`jPanel1 = new Fahim();`

```powershell
import java.awt.Color;
import java.awt.GradientPaint;
import java.awt.Graphics;
import java.awt.Graphics2D;
import javax.swing.JPanel;

/**
 *
 * @author Mahady Hasan Fahim
 * 
 */



class Fahim extends JPanel {
    protected void paintComponent(Graphics g) {
        super.paintComponent(g);
        Graphics2D g2d = (Graphics2D) g;
        int width = getWidth();
        int height = getHeight();
        Color color1 = new Color(52, 143, 80);
        Color color2 = new Color(86, 180, 211);

        GradientPaint gp = new GradientPaint(0, 0, color1, 180, height, color2);
        g2d.setPaint(gp);
        g2d.fillRect(0, 0, width, height);
    }
}

```
