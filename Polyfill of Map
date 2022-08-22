//polyfill of map
Array.prototype.ourMap = function (cb) {
  let temp = [];
  for(let item of this) {
    temp.push(cb(item))
  }
  return temp
}

Array.prototype.yourMap = function (cb) {
  let temp = [];
  for(let i = 0 ; i < this.length; i++) {
    temp.push(cb(this[i],i,this))
  }
  return temp
}




const nums =[1,2,3,4]

const ok = nums.ourMap((num) => {
  return num * 3
})

console.log(ok)
