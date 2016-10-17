# progress-bar
A simple and very light weight responsive javascript progress bar library having checkpoints.

To use this library just include in your html file in the script tag.
and in your application:
> ProgressBar.init(
>    [ 'checkpoint-1',
>      'checkpoint-2',
>      ...,
>      ...,
>      'checkpoint-n'
>    ],
>    'current-checkpoint',
>    'wrapper div(optional)'
>  );

You can modify styles from css/main.css, according to your requirement
Also you can modify animation duration as per your requirement.
> ProgressBar.singleStepAnimation = 1500

See the example file to understand more.
