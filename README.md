# Self_Driving



<pre><code>```mermaid graph TD Selector["? Selector: Main Behavior Tree"] Selector --> Seq1["→ Sequence: Crosswalk Stop"] Seq1 --> C1["Condition: is_crosswalk_near"] Seq1 --> A1["Action: stop_and_wait"] Selector --> Seq2["→ Sequence: Red Light Stop"] Seq2 --> C2["Condition: is_red_light"] Seq2 --> A2["Action: stop_vehicle"] Selector --> Seq3["→ Sequence: Turn Right"] Seq3 --> C3["Condition: is_turn_right_detected"] Seq3 --> A3["Action: turn_right"] Selector --> Seq4["→ Sequence: Park"] Seq4 --> C4["Condition: is_park_detected"] Seq4 --> A4["Action: park_and_shutdown"] Selector --> A5["Action: follow_lane (fallback)"] ```</code></pre>
