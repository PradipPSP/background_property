# background_property

Note:

1. Background Color Property:

    1. background-color: red; {Solid color}

    /* linear gradient */
    1. background: linear-gradient(to left, red, blue); {Starts with left} [Best Used]
    2. background: linear-gradient(to top, red, blue); {Starts with top}
    3. background: linear-gradient(to bottom, red, blue); {Starts with bottom}
    4. background: linear-gradient(to right, red, blue); {Starts with right}
    5. background: linear-gradient(45 deg, red, blue);
    6. background: linear-gradient(180 deg, red, blue);

    /* radial gradient */
    1. background: radial-gradient (circle, red, blue);
    2. background: radial-gradient (squire, red, blue);

    /* conic gradient */
    1. background: radial-gradient (red, blue);
    2. background: radial-gradient (red, blue);

2. Background Image Property:

    1. background-image: url("") [Direct link]
    2. background-image: url("./rsc/bg-jpg") [Internal link]

    1. background-repeat: no-repeat [Recommended]
    2. background-repeat: repeat-x [left to right]
    3. background-repeat: repeat-y [top to bottom]
     
    1. background-size: 100px; [rectangle view]
    2. background-size: 100px 100px; [squire view]
    3. background-size: auto; [dafult]
    4. background-size: cover; [Recommended]
    5. background-size: contain; [শুধুমাত্র যতটুকু কনেটন্ট থাকবে ততটুকু কভার করবে]

    1. background-position: top; [default] [ছবির উপর হতে শুরু হবে]
    2. background-position: bottom; 
    3. background-position: center center; [Recommended]

    1. border-radius: 20px 10px 5px 3px; [top-left, top-right, bottom-right & bottom-left] (Like as Watch)
    2. border-radius: 20px 10px; [top-left & bottom-right And top-right & left-bottom]

    Note: 
    1. background-repeat: no-repeat;
    2. background-size: cover;
    3. background-position: center center;
    
    2. Block-Element এর default কোন height width থাকে না
    3. rgb color(red, green, blue)
    4. web page শুরু থেকে রিড করে অর্থাৎ একই প্রোপার্টি দুইটি ব্যবহার করলে ১ম টির ভ্যালু গ্রহণযোগ্য নয়। অর্থাৎ   সর্বশেষ ভ্যাটু টি শো করবে।
    