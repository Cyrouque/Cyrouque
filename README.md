import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        // Trouver le TextView dans le layout
        TextView textView = findViewById(R.id.textView);

        // Modifier le texte pour afficher "Bonjour"
        textView.setText("Bonjour !");
    }
}
