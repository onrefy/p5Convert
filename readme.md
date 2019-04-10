# p5替代计划

---

在意识到p5局限性后决定找到别的方式去替代p5的计划

计划包括一下几个部分：

1. p5功能列表
2. 从canvas的2d替换
3. 从webgl的3d替换

---

## p5功能列表

#### 颜色

- 创造及读取

  [alpha()](https://p5js.org/zh-Hans/reference/#/p5/alpha)

  [blue()](https://p5js.org/zh-Hans/reference/#/p5/blue)

  [brightness()](https://p5js.org/zh-Hans/reference/#/p5/brightness)

  [color()](https://p5js.org/zh-Hans/reference/#/p5/color)

  [green()](https://p5js.org/zh-Hans/reference/#/p5/green)

  [hue()](https://p5js.org/zh-Hans/reference/#/p5/hue)

  [lerpColor()](https://p5js.org/zh-Hans/reference/#/p5/lerpColor)

  [lightness()](https://p5js.org/zh-Hans/reference/#/p5/lightness)

  [red()](https://p5js.org/zh-Hans/reference/#/p5/red)

  [saturation()](https://p5js.org/zh-Hans/reference/#/p5/saturation)

  [p5.Color](https://p5js.org/zh-Hans/reference/#/p5.Color)

- 设置

  [background()](https://p5js.org/zh-Hans/reference/#/p5/background)

  [clear()](https://p5js.org/zh-Hans/reference/#/p5/clear)

  [colorMode()](https://p5js.org/zh-Hans/reference/#/p5/colorMode)

  [fill()](https://p5js.org/zh-Hans/reference/#/p5/fill)

  [noFill()](https://p5js.org/zh-Hans/reference/#/p5/noFill)

  [noStroke()](https://p5js.org/zh-Hans/reference/#/p5/noStroke)

  [stroke()](https://p5js.org/zh-Hans/reference/#/p5/stroke)

#### 形状

- 2D 形状

  [arc()](https://p5js.org/zh-Hans/reference/#/p5/arc)

  [ellipse()](https://p5js.org/zh-Hans/reference/#/p5/ellipse)

  [circle()](https://p5js.org/zh-Hans/reference/#/p5/circle)

  [line()](https://p5js.org/zh-Hans/reference/#/p5/line)

  [point()](https://p5js.org/zh-Hans/reference/#/p5/point)

  [quad()](https://p5js.org/zh-Hans/reference/#/p5/quad)

  [rect()](https://p5js.org/zh-Hans/reference/#/p5/rect)

  [square()](https://p5js.org/zh-Hans/reference/#/p5/square)

  [triangle()](https://p5js.org/zh-Hans/reference/#/p5/triangle)

- 属性

  [ellipseMode()](https://p5js.org/zh-Hans/reference/#/p5/ellipseMode)

  [noSmooth()](https://p5js.org/zh-Hans/reference/#/p5/noSmooth)

  [rectMode()](https://p5js.org/zh-Hans/reference/#/p5/rectMode)

  [smooth()](https://p5js.org/zh-Hans/reference/#/p5/smooth)

  [strokeCap()](https://p5js.org/zh-Hans/reference/#/p5/strokeCap)

  [strokeJoin()](https://p5js.org/zh-Hans/reference/#/p5/strokeJoin)

  [strokeWeight()](https://p5js.org/zh-Hans/reference/#/p5/strokeWeight)

- 弧形

  [bezier()](https://p5js.org/zh-Hans/reference/#/p5/bezier)

  [bezierDetail()](https://p5js.org/zh-Hans/reference/#/p5/bezierDetail)

  [bezierPoint()](https://p5js.org/zh-Hans/reference/#/p5/bezierPoint)

  [bezierTangent()](https://p5js.org/zh-Hans/reference/#/p5/bezierTangent)

  [curve()](https://p5js.org/zh-Hans/reference/#/p5/curve)

  [curveDetail()](https://p5js.org/zh-Hans/reference/#/p5/curveDetail)

  [curveTightness()](https://p5js.org/zh-Hans/reference/#/p5/curveTightness)

  [curvePoint()](https://p5js.org/zh-Hans/reference/#/p5/curvePoint)

  [curveTangent()](https://p5js.org/zh-Hans/reference/#/p5/curveTangent)

- 顶点

  [beginContour()](https://p5js.org/zh-Hans/reference/#/p5/beginContour)

  [beginShape()](https://p5js.org/zh-Hans/reference/#/p5/beginShape)

  [bezierVertex()](https://p5js.org/zh-Hans/reference/#/p5/bezierVertex)

  [curveVertex()](https://p5js.org/zh-Hans/reference/#/p5/curveVertex)

  [endContour()](https://p5js.org/zh-Hans/reference/#/p5/endContour)

  [endShape()](https://p5js.org/zh-Hans/reference/#/p5/endShape)

  [quadraticVertex()](https://p5js.org/zh-Hans/reference/#/p5/quadraticVertex)

  [vertex()](https://p5js.org/zh-Hans/reference/#/p5/vertex)

- 3D 形状

  [plane()](https://p5js.org/zh-Hans/reference/#/p5/plane)

  [box()](https://p5js.org/zh-Hans/reference/#/p5/box)

  [sphere()](https://p5js.org/zh-Hans/reference/#/p5/sphere)

  [cylinder()](https://p5js.org/zh-Hans/reference/#/p5/cylinder)

  [cone()](https://p5js.org/zh-Hans/reference/#/p5/cone)

  [ellipsoid()](https://p5js.org/zh-Hans/reference/#/p5/ellipsoid)

  [torus()](https://p5js.org/zh-Hans/reference/#/p5/torus)

- 3D 模型

  [loadModel()](https://p5js.org/zh-Hans/reference/#/p5/loadModel)

  [model()](https://p5js.org/zh-Hans/reference/#/p5/model)

#### 资料

- 字典

  [createStringDict()](https://p5js.org/zh-Hans/reference/#/p5/createStringDict)

  [createNumberDict()](https://p5js.org/zh-Hans/reference/#/p5/createNumberDict)

  [p5.TypedDict](https://p5js.org/zh-Hans/reference/#/p5.TypedDict)

  [p5.NumberDict](https://p5js.org/zh-Hans/reference/#/p5.NumberDict)

- 数组函数

  [append()](https://p5js.org/zh-Hans/reference/#/p5/append)

  [arrayCopy()](https://p5js.org/zh-Hans/reference/#/p5/arrayCopy)

  [concat()](https://p5js.org/zh-Hans/reference/#/p5/concat)

  [reverse()](https://p5js.org/zh-Hans/reference/#/p5/reverse)

  [shorten()](https://p5js.org/zh-Hans/reference/#/p5/shorten)

  [shuffle()](https://p5js.org/zh-Hans/reference/#/p5/shuffle)

  [sort()](https://p5js.org/zh-Hans/reference/#/p5/sort)

  [splice()](https://p5js.org/zh-Hans/reference/#/p5/splice)

  [subset()](https://p5js.org/zh-Hans/reference/#/p5/subset)

- 转换

  [float()](https://p5js.org/zh-Hans/reference/#/p5/float)

  [int()](https://p5js.org/zh-Hans/reference/#/p5/int)

  [str()](https://p5js.org/zh-Hans/reference/#/p5/str)

  [boolean()](https://p5js.org/zh-Hans/reference/#/p5/boolean)

  [byte()](https://p5js.org/zh-Hans/reference/#/p5/byte)

  [char()](https://p5js.org/zh-Hans/reference/#/p5/char)

  [unchar()](https://p5js.org/zh-Hans/reference/#/p5/unchar)

  [hex()](https://p5js.org/zh-Hans/reference/#/p5/hex)

  [unhex()](https://p5js.org/zh-Hans/reference/#/p5/unhex)

- 字符串函数

  [join()](https://p5js.org/zh-Hans/reference/#/p5/join)

  [match()](https://p5js.org/zh-Hans/reference/#/p5/match)

  [matchAll()](https://p5js.org/zh-Hans/reference/#/p5/matchAll)

  [nf()](https://p5js.org/zh-Hans/reference/#/p5/nf)

  [nfc()](https://p5js.org/zh-Hans/reference/#/p5/nfc)

  [nfp()](https://p5js.org/zh-Hans/reference/#/p5/nfp)

  [nfs()](https://p5js.org/zh-Hans/reference/#/p5/nfs)

  [split()](https://p5js.org/zh-Hans/reference/#/p5/split)

  [splitTokens()](https://p5js.org/zh-Hans/reference/#/p5/splitTokens)

  [trim()](https://p5js.org/zh-Hans/reference/#/p5/trim)

#### 事件

- 加速度

  [deviceOrientation](https://p5js.org/zh-Hans/reference/#/p5/deviceOrientation)

  [accelerationX](https://p5js.org/zh-Hans/reference/#/p5/accelerationX)

  [accelerationY](https://p5js.org/zh-Hans/reference/#/p5/accelerationY)

  [accelerationZ](https://p5js.org/zh-Hans/reference/#/p5/accelerationZ)

  [pAccelerationX](https://p5js.org/zh-Hans/reference/#/p5/pAccelerationX)

  [pAccelerationY](https://p5js.org/zh-Hans/reference/#/p5/pAccelerationY)

  [pAccelerationZ](https://p5js.org/zh-Hans/reference/#/p5/pAccelerationZ)

  [rotationX](https://p5js.org/zh-Hans/reference/#/p5/rotationX)

  [rotationY](https://p5js.org/zh-Hans/reference/#/p5/rotationY)

  [rotationZ](https://p5js.org/zh-Hans/reference/#/p5/rotationZ)

  [pRotationX](https://p5js.org/zh-Hans/reference/#/p5/pRotationX)

  [pRotationY](https://p5js.org/zh-Hans/reference/#/p5/pRotationY)

  [pRotationZ](https://p5js.org/zh-Hans/reference/#/p5/pRotationZ)

  [turnAxis](https://p5js.org/zh-Hans/reference/#/p5/turnAxis)

  [setMoveThreshold()](https://p5js.org/zh-Hans/reference/#/p5/setMoveThreshold)

  [setShakeThreshold()](https://p5js.org/zh-Hans/reference/#/p5/setShakeThreshold)

  [deviceMoved()](https://p5js.org/zh-Hans/reference/#/p5/deviceMoved)

  [deviceTurned()](https://p5js.org/zh-Hans/reference/#/p5/deviceTurned)

  [deviceShaken()](https://p5js.org/zh-Hans/reference/#/p5/deviceShaken)

- 键盘

  [keyIsPressed](https://p5js.org/zh-Hans/reference/#/p5/keyIsPressed)

  [key](https://p5js.org/zh-Hans/reference/#/p5/key)

  [keyCode](https://p5js.org/zh-Hans/reference/#/p5/keyCode)

  [keyPressed()](https://p5js.org/zh-Hans/reference/#/p5/keyPressed)

  [keyReleased()](https://p5js.org/zh-Hans/reference/#/p5/keyReleased)

  [keyTyped()](https://p5js.org/zh-Hans/reference/#/p5/keyTyped)

  [keyIsDown()](https://p5js.org/zh-Hans/reference/#/p5/keyIsDown)

- 滑鼠

  [mouseX](https://p5js.org/zh-Hans/reference/#/p5/mouseX)

  [mouseY](https://p5js.org/zh-Hans/reference/#/p5/mouseY)

  [pmouseX](https://p5js.org/zh-Hans/reference/#/p5/pmouseX)

  [pmouseY](https://p5js.org/zh-Hans/reference/#/p5/pmouseY)

  [winMouseX](https://p5js.org/zh-Hans/reference/#/p5/winMouseX)

  [winMouseY](https://p5js.org/zh-Hans/reference/#/p5/winMouseY)

  [pwinMouseX](https://p5js.org/zh-Hans/reference/#/p5/pwinMouseX)

  [pwinMouseY](https://p5js.org/zh-Hans/reference/#/p5/pwinMouseY)

  [mouseButton](https://p5js.org/zh-Hans/reference/#/p5/mouseButton)

  [mouseIsPressed](https://p5js.org/zh-Hans/reference/#/p5/mouseIsPressed)

  [mouseMoved()](https://p5js.org/zh-Hans/reference/#/p5/mouseMoved)

  [mouseDragged()](https://p5js.org/zh-Hans/reference/#/p5/mouseDragged)

  [mousePressed()](https://p5js.org/zh-Hans/reference/#/p5/mousePressed)

  [mouseReleased()](https://p5js.org/zh-Hans/reference/#/p5/mouseReleased)

  [mouseClicked()](https://p5js.org/zh-Hans/reference/#/p5/mouseClicked)

  [doubleClicked()](https://p5js.org/zh-Hans/reference/#/p5/doubleClicked)

  [mouseWheel()](https://p5js.org/zh-Hans/reference/#/p5/mouseWheel)

- 触动

  [touches](https://p5js.org/zh-Hans/reference/#/p5/touches)

  [touchStarted()](https://p5js.org/zh-Hans/reference/#/p5/touchStarted)

  [touchMoved()](https://p5js.org/zh-Hans/reference/#/p5/touchMoved)

  [touchEnded()](https://p5js.org/zh-Hans/reference/#/p5/touchEnded)

#### 图像



- 加载和显示

  [loadImage()](https://p5js.org/zh-Hans/reference/#/p5/loadImage)

  [image()](https://p5js.org/zh-Hans/reference/#/p5/image)

  [tint()](https://p5js.org/zh-Hans/reference/#/p5/tint)

  [noTint()](https://p5js.org/zh-Hans/reference/#/p5/noTint)

  [imageMode()](https://p5js.org/zh-Hans/reference/#/p5/imageMode)

- 像素

  [pixels](https://p5js.org/zh-Hans/reference/#/p5/pixels)

  [blend()](https://p5js.org/zh-Hans/reference/#/p5/blend)

  [copy()](https://p5js.org/zh-Hans/reference/#/p5/copy)

  [filter()](https://p5js.org/zh-Hans/reference/#/p5/filter)

  [get()](https://p5js.org/zh-Hans/reference/#/p5/get)

  [loadPixels()](https://p5js.org/zh-Hans/reference/#/p5/loadPixels)

  [set()](https://p5js.org/zh-Hans/reference/#/p5/set)

  [updatePixels()](https://p5js.org/zh-Hans/reference/#/p5/updatePixels)

#### 输入和输出

- 输入

  [loadJSON()](https://p5js.org/zh-Hans/reference/#/p5/loadJSON)

  [loadStrings()](https://p5js.org/zh-Hans/reference/#/p5/loadStrings)

  [loadTable()](https://p5js.org/zh-Hans/reference/#/p5/loadTable)

  [loadXML()](https://p5js.org/zh-Hans/reference/#/p5/loadXML)

  [loadBytes()](https://p5js.org/zh-Hans/reference/#/p5/loadBytes)

  [httpGet()](https://p5js.org/zh-Hans/reference/#/p5/httpGet)

  [httpPost()](https://p5js.org/zh-Hans/reference/#/p5/httpPost)

  [httpDo()](https://p5js.org/zh-Hans/reference/#/p5/httpDo)

- 输出

  [createWriter()](https://p5js.org/zh-Hans/reference/#/p5/createWriter)

  [p5.PrintWriter](https://p5js.org/zh-Hans/reference/#/p5.PrintWriter)

  [save()](https://p5js.org/zh-Hans/reference/#/p5/save)

  [saveJSON()](https://p5js.org/zh-Hans/reference/#/p5/saveJSON)

  [saveStrings()](https://p5js.org/zh-Hans/reference/#/p5/saveStrings)

  [saveTable()](https://p5js.org/zh-Hans/reference/#/p5/saveTable)

- 表格

  [p5.Table](https://p5js.org/zh-Hans/reference/#/p5.Table)

  [p5.TableRow](https://p5js.org/zh-Hans/reference/#/p5.TableRow)

- XML

  [p5.XML](https://p5js.org/zh-Hans/reference/#/p5.XML)

- 时间和日期

  [day()](https://p5js.org/zh-Hans/reference/#/p5/day)

  [hour()](https://p5js.org/zh-Hans/reference/#/p5/hour)

  [minute()](https://p5js.org/zh-Hans/reference/#/p5/minute)

  [millis()](https://p5js.org/zh-Hans/reference/#/p5/millis)

  [month()](https://p5js.org/zh-Hans/reference/#/p5/month)

  [second()](https://p5js.org/zh-Hans/reference/#/p5/second)

  [year()](https://p5js.org/zh-Hans/reference/#/p5/year)

#### 数学



- 计算

  [abs()](https://p5js.org/zh-Hans/reference/#/p5/abs)

  [ceil()](https://p5js.org/zh-Hans/reference/#/p5/ceil)

  [constrain()](https://p5js.org/zh-Hans/reference/#/p5/constrain)

  [dist()](https://p5js.org/zh-Hans/reference/#/p5/dist)

  [exp()](https://p5js.org/zh-Hans/reference/#/p5/exp)

  [floor()](https://p5js.org/zh-Hans/reference/#/p5/floor)

  [lerp()](https://p5js.org/zh-Hans/reference/#/p5/lerp)

  [log()](https://p5js.org/zh-Hans/reference/#/p5/log)

  [mag()](https://p5js.org/zh-Hans/reference/#/p5/mag)

  [map()](https://p5js.org/zh-Hans/reference/#/p5/map)

  [max()](https://p5js.org/zh-Hans/reference/#/p5/max)

  [min()](https://p5js.org/zh-Hans/reference/#/p5/min)

  [norm()](https://p5js.org/zh-Hans/reference/#/p5/norm)

  [pow()](https://p5js.org/zh-Hans/reference/#/p5/pow)

  [round()](https://p5js.org/zh-Hans/reference/#/p5/round)

  [sq()](https://p5js.org/zh-Hans/reference/#/p5/sq)

  [sqrt()](https://p5js.org/zh-Hans/reference/#/p5/sqrt)

- 噪声

  [noise()](https://p5js.org/zh-Hans/reference/#/p5/noise)

  [noiseDetail()](https://p5js.org/zh-Hans/reference/#/p5/noiseDetail)

  [noiseSeed()](https://p5js.org/zh-Hans/reference/#/p5/noiseSeed)

- Random

  [randomSeed()](https://p5js.org/zh-Hans/reference/#/p5/randomSeed)

  [random()](https://p5js.org/zh-Hans/reference/#/p5/random)

  [randomGaussian()](https://p5js.org/zh-Hans/reference/#/p5/randomGaussian)

- 三角学

  [acos()](https://p5js.org/zh-Hans/reference/#/p5/acos)

  [asin()](https://p5js.org/zh-Hans/reference/#/p5/asin)

  [atan()](https://p5js.org/zh-Hans/reference/#/p5/atan)

  [atan2()](https://p5js.org/zh-Hans/reference/#/p5/atan2)

  [cos()](https://p5js.org/zh-Hans/reference/#/p5/cos)

  [sin()](https://p5js.org/zh-Hans/reference/#/p5/sin)

  [tan()](https://p5js.org/zh-Hans/reference/#/p5/tan)

  [degrees()](https://p5js.org/zh-Hans/reference/#/p5/degrees)

  [radians()](https://p5js.org/zh-Hans/reference/#/p5/radians)

  [angleMode()](https://p5js.org/zh-Hans/reference/#/p5/angleMode)

#### 字体

- 属性

  [textAlign()](https://p5js.org/zh-Hans/reference/#/p5/textAlign)

  [textLeading()](https://p5js.org/zh-Hans/reference/#/p5/textLeading)

  [textSize()](https://p5js.org/zh-Hans/reference/#/p5/textSize)

  [textStyle()](https://p5js.org/zh-Hans/reference/#/p5/textStyle)

  [textWidth()](https://p5js.org/zh-Hans/reference/#/p5/textWidth)

  [textAscent()](https://p5js.org/zh-Hans/reference/#/p5/textAscent)

  [textDescent()](https://p5js.org/zh-Hans/reference/#/p5/textDescent)

- 加载和显示

  [loadFont()](https://p5js.org/zh-Hans/reference/#/p5/loadFont)

  [text()](https://p5js.org/zh-Hans/reference/#/p5/text)

  [textFont()](https://p5js.org/zh-Hans/reference/#/p5/textFont)

- 字形

  [p5.Font](https://p5js.org/zh-Hans/reference/#/p5.Font)

#### 灯光、相机

- Interaction

  [orbitControl()](https://p5js.org/zh-Hans/reference/#/p5/orbitControl)

  [debugMode()](https://p5js.org/zh-Hans/reference/#/p5/debugMode)

  [noDebugMode()](https://p5js.org/zh-Hans/reference/#/p5/noDebugMode)

- 灯光

  [ambientLight()](https://p5js.org/zh-Hans/reference/#/p5/ambientLight)

  [directionalLight()](https://p5js.org/zh-Hans/reference/#/p5/directionalLight)

  [pointLight()](https://p5js.org/zh-Hans/reference/#/p5/pointLight)

  [lights()](https://p5js.org/zh-Hans/reference/#/p5/lights)

- 材料

  [loadShader()](https://p5js.org/zh-Hans/reference/#/p5/loadShader)

  [createShader()](https://p5js.org/zh-Hans/reference/#/p5/createShader)

  [shader()](https://p5js.org/zh-Hans/reference/#/p5/shader)

  [resetShader()](https://p5js.org/zh-Hans/reference/#/p5/resetShader)

  [normalMaterial()](https://p5js.org/zh-Hans/reference/#/p5/normalMaterial)

  [texture()](https://p5js.org/zh-Hans/reference/#/p5/texture)

  [textureMode()](https://p5js.org/zh-Hans/reference/#/p5/textureMode)

  [textureWrap()](https://p5js.org/zh-Hans/reference/#/p5/textureWrap)

  [ambientMaterial()](https://p5js.org/zh-Hans/reference/#/p5/ambientMaterial)

  [specularMaterial()](https://p5js.org/zh-Hans/reference/#/p5/specularMaterial)

  [shininess()](https://p5js.org/zh-Hans/reference/#/p5/shininess)

- 相机

  [camera()](https://p5js.org/zh-Hans/reference/#/p5/camera)

  [perspective()](https://p5js.org/zh-Hans/reference/#/p5/perspective)

  [ortho()](https://p5js.org/zh-Hans/reference/#/p5/ortho)

  [createCamera()](https://p5js.org/zh-Hans/reference/#/p5/createCamera)

  [p5.Camera](https://p5js.org/zh-Hans/reference/#/p5.Camera)

  [setCamera()](https://p5js.org/zh-Hans/reference/#/p5/setCamera)

- Shaders

  [p5.Shader](https://p5js.org/zh-Hans/reference/#/p5.Shader)