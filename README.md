# Delay-function-call
 
function wait(ms) {
 return new Promise(resolve => setTimeout(resolve, ms)); 
}
wait(5000).then(() => {
 console.log('5 seconds have passed...');
});
