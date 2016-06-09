###2.1.离心调速器

　　对控制设备的需要此时已经出现在风车的操作上。回溯到1745年，当时发明的离心调速器就是为了风车保持恒定转速运行(Mayr,1969)。类似的需求也出现在使用蒸汽动力的纺织业，他们需要使织布机和其他机器保持恒定转速。吉姆斯.瓦特成功地改造了离心调速器，并将其用于蒸汽机并在1788申请了专利。
  
　　离心调速器包含传感、执行和控制。设计调速器是一个折中办法：需要沉重的飞球产生大的驱动力，但是也会导致反应迟缓。实践上还遇到了机械设施中摩擦力和间隙的难题。基本的调速器产生比例作用，因为飞球连杆与转轴的角度同转轴速度成比例关系。这样的调速器会产生稳态误差，但是附有积分作用的控制器却具有总能接近正确稳态的特质，如果闭环系统是稳定。1790年左右，Pérrier兄弟设计的调速器中引入了积分作用。他们使用了一个液压装置，在装置中流入容器的液体量和速度成比例关系，而且蒸汽阀由液位控制(Mayr, 1969, p. 110–113)。1845年，Werner和William Siemens通过差速齿轮引入了积分作用(Bennett, 1979, p. 21–22)。Siemens兄弟还基于惯性轮引入了微分作用。自此调速器成了蒸汽机不可分割的一部分，而在18世纪末的后200年调速器也得到了发展。Bennett对此进行了详细的描述 (Bennett. 1979) 。
  
　　调速器的理论研究是从麦克斯韦（Maxwell） 的论文开始的 (Maxwell. 1868) 。他分析了线性模型还证明了积分作用的优点。他同时发现可以通过闭环系统特征方程的根确定系统的稳定性。麦克斯韦推导出三阶系统的稳定性判据并求助于劳斯（Routh），后者解决了一般性的问题 (Routh, 1877)。Vyshnegradskii独立于麦克斯韦分析了带有调速器的蒸汽机，也开发出一个三阶系统的稳定性判据(Vyshnegradskii, 1876)。Vyshnegradskii的工作是工程导向的，而且与调速器的设计紧密结合。他被训练成为一名数学家还是圣彼得堡国立技术学院的主任。在那里他开创了有强大科学基础的机械制造课程。他在沙皇俄国财政部长的任上结束了他的事业生涯(Andronov, 1978)。
  
　　Vyshnegradskii的研究成果被Stodola用来设计水轮机调速器。他用到了更复杂的模型还求助了他在苏黎士联邦理工学院（ETH）的同事赫尔维茨（Hurwitz），后者主要帮助做稳定性分析。赫尔维茨用不同于劳斯的其他方法推导出一个一般性的稳定性判据(Hurwitz, 1895)，即今天众所周知的结论—劳斯-赫尔维茨判据。Stodola还引入了无量纲变量和时间常数。Andronov(1978)、Bennett(1979)、Bissell(1989)和Profos(1976)提供了关于麦克斯韦和Vyshnegradskii工作的有趣观点。这时的科学家们很少互动(Gantmacher, 1960, p.172–173)。劳斯和赫尔维茨没有意识到彼此的贡献，而且他们也采用了不同的数学技巧 (Lyapunov,1892)。Stodola只是在他后来的文章中提到了劳斯(Andronov, 1978)。
  
　　19世纪初期牢固建立了控制带调速器机器的工程学基础。许多公司发明和制造了调速器。据Bennett(1979, page74)说，在1868年，英格兰安装了75000多台调速器。人们理解了比例积分和微分的作用并将其应用在机械和液压装置上。这些理论基础是建立在麦克斯韦、Vyshnegradskii和劳斯-赫尔维茨判据的研究成果上。控制的教育是从少数大学开始的。Tolle在1905年将研究成果编辑到教科书《Der Regelung der Kraftmaschinen (Control of Power Machines)》中。分析和设计都是在线性化和检验特征方程根的基础上。在1909年，莫斯科大学的空气动力学家Joukowski出版了第一本控制方面的俄文书《The Theory of Regulating the Motion of Machines》。