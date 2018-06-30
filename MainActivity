package com.example.android.quizappp;

import android.app.Activity;
import android.content.Intent;
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;

public class MainActivity extends AppCompatActivity {

public Button buttononclick;
private Activity activity;



    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        activity = this;
        buttononclick =(Button)findViewById(R.id.click_botton);
        buttononclick.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {


                Intent toy =new Intent(activity, Main2Activity.class);
                startActivity(toy);
            }
        });

    }
}
