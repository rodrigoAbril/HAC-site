# HAC-site
backup for HAC site files


## generating videos

The functionality is very simple and requires minimal input

this block of code will generate a video block with title and subtitle


```HTML
  <div class="generateVideo"
       data-video="0000000?h=0a0a0a0a0a"
       data-aspectratio="aspectRatio1x1"
       data-title="Video Title"
       data-subtitle="Video Subtitle"
       data-modal="true"
       data-link="/url"
  ></div>
```

- `data-video` : vimeo video ids you can get them from the video url or from vimeo the embed code.
- `data-aspectratio` : The options are `aspectRatio1x1`, `aspectRatio16x9`, `aspectRatio4x3`, `aspectRatio4x5`.
- `data-title` : The Video Title it will be displayed in the first line under the video.
- `data-subtitle` : The Video Subtitle it will be displayed in the second line under the video title (no need to add the Pluss Icon).
- `data-modal` : if `true` clicing the Video or titles will open a modal with the vimeo video with player controls, if its `true` it will ignore the next value.
- `data-link` : the url that will be opened when clicking ( only works if `data-modal="false"`).
