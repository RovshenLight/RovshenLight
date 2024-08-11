<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background: linear-gradient(308deg, rgba(20,51,3,1) 0%, rgba(26,31,0,1) 52%, rgba(97,79,0,1) 100%);
      background-size: 400% 400%;
      animation: gradientAnimation 15s ease infinite;
      margin: 0;
      padding: 0;
      height: 100vh;
    }

    @keyframes gradientAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    div {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
  </style>
</head>
<body>
  <div>
    <img height="200" src="https://cdn.svgator.com/images/2021/10/solar-system-animation.svg" />
  </div>
  
  <div align="center">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RovshenLight&theme=neon&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="GitHub Top Languages"/>
  </div>
</body>
</html>
