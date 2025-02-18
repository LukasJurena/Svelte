<script>
	import { LottiePlayer } from '@lottiefiles/svelte-lottie-player';
</script>

<LottiePlayer
  src='https://assets2.lottiefiles.com/packages/lf20_wxUJzo.json'
  autoplay={true}
  loop={true}
  controls={true}
  renderer='svg'
  background='transparent'
  height={500}
  width={500}
  controlsLayout={[
		"previousFrame",
		"playpause",
		"stop",
		"nextFrame",
		"progress",
		"frame",
		"loop",
		"spacer",
		"background",
		"snapshot",
		"zoom",
		"info"
	]} />