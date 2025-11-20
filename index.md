---
layout: home
title: 我的工具集 | 个人小工具合集
author_profile: true
classes: wide
permalink: /
---

<!-- 英雄区域 -->
<section class="py-12 md:py-20 bg-gradient-to-r from-blue-50 to-purple-50 rounded-b-3xl">
  <div class="container mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex flex-col md:flex-row items-center">
      <div class="md:w-1/2 mb-10 md:mb-0 md:pr-8">
        <h1 class="text-[clamp(2rem,5vw,3.5rem)] font-bold leading-tight mb-4">
          实用小工具<br>
          <span class="bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent">
            提升你的效率
          </span>
        </h1>
        <p class="text-gray-700 text-lg md:text-xl mb-8 max-w-lg">
          这里收集了我开发的各类实用小工具，涵盖日常办公、设计辅助、编程开发等多个场景，帮助你简化工作流程，节省宝贵时间。
        </p>
        <a href="#tools" class="inline-flex items-center px-6 py-3 bg-blue-600 hover:bg-blue-700 text-white font-medium rounded-lg shadow-md hover:shadow-lg transition-all duration-300">
          浏览工具集
          <i class="fa fa-arrow-right ml-2"></i>
        </a>
      </div>
      <div class="md:w-1/2 relative">
        <div class="absolute -inset-4 bg-gradient-to-r from-blue-100 to-purple-100 rounded-2xl blur-xl opacity-70"></div>
        <img src="https://picsum.photos/id/180/600/400" alt="工具集展示" class="relative rounded-xl shadow-2xl w-full h-auto object-cover" loading="lazy">
        <div class="absolute -bottom-6 -right-6 bg-white p-4 rounded-lg shadow-lg hidden md:block">
          <div class="flex items-center space-x-2">
            <div class="w-3 h-3 rounded-full bg-green-500 animate-pulse"></div>
            <span class="font-medium">20+ 实用工具</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 工具展示区域 -->
<section id="tools" class="py-16 md:py-24">
  <div class="container mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16">
      <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold mb-4">我的工具集</h2>
      <p class="text-gray-700 max-w-2xl mx-auto text-lg">
        精心开发的各类小工具，解决实际问题，提升工作与生活效率
      </p>
      
      <!-- 分类筛选按钮 -->
      <div class="mt-8 flex flex-wrap justify-center gap-3" id="tool-filters">
        <button class="tool-filter active px-4 py-2 rounded-full bg-blue-600 text-white font-medium" data-category="all">全部工具</button>
        <button class="tool-filter px-4 py-2 rounded-full bg-gray-100 hover:bg-gray-200 font-medium transition-colors" data-category="productivity">效率工具</button>
        <button class="tool-filter px-4 py-2 rounded-full bg-gray-100 hover:bg-gray-200 font-medium transition-colors" data-category="design">设计工具</button>
        <button class="tool-filter px-4 py-2 rounded-full bg-gray-100 hover:bg-gray-200 font-medium transition-colors" data-category="development">开发工具</button>
        <button class="tool-filter px-4 py-2 rounded-full bg-gray-100 hover:bg-gray-200 font-medium transition-colors" data-category="utilities">实用工具</button>
      </div>
    </div>

    <!-- 工具卡片网格 -->
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8" id="tool-grid">
      <!-- 工具卡片 1 -->
      <div class="tool-card" data-category="productivity">
        <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-xl hover:-translate-y-1">
          <div class="h-48 overflow-hidden">
            <img src="https://picsum.photos/id/0/600/400" alt="文本转换器" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110" loading="lazy">
          </div>
          <div class="p-6">
            <div class="flex justify-between items-start mb-3">
              <span class="px-3 py-1 bg-blue-100 text-blue-600 text-sm font-medium rounded-full">效率工具</span>
              <div class="flex space-x-1">
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star-half-o text-yellow-400"></i>
              </div>
            </div>
            <h3 class="text-xl font-bold mb-2">多功能文本转换器</h3>
            <p class="text-gray-700 mb-4">支持文本格式转换、大小写转换、特殊字符处理等多种功能，提升文案处理效率。</p>
            <a href="#" class="inline-flex items-center text-blue-600 font-medium hover:text-blue-700 transition-colors">
              立即使用
              <i class="fa fa-external-link ml-1"></i>
            </a>
          </div>
        </div>
      </div>

      <!-- 工具卡片 2 -->
      <div class="tool-card" data-category="design">
        <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-xl hover:-translate-y-1">
          <div class="h-48 overflow-hidden">
            <img src="https://picsum.photos/id/96/600/400" alt="颜色搭配工具" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110" loading="lazy">
          </div>
          <div class="p-6">
            <div class="flex justify-between items-start mb-3">
              <span class="px-3 py-1 bg-purple-100 text-purple-600 text-sm font-medium rounded-full">设计工具</span>
              <div class="flex space-x-1">
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
              </div>
            </div>
            <h3 class="text-xl font-bold mb-2">智能颜色搭配工具</h3>
            <p class="text-gray-700 mb-4">快速生成和谐的颜色方案，支持多种配色模式，导出多种格式，设计工作的好帮手。</p>
            <a href="#" class="inline-flex items-center text-blue-600 font-medium hover:text-blue-700 transition-colors">
              立即使用
              <i class="fa fa-external-link ml-1"></i>
            </a>
          </div>
        </div>
      </div>

      <!-- 工具卡片 3 -->
      <div class="tool-card" data-category="development">
        <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-xl hover:-translate-y-1">
          <div class="h-48 overflow-hidden">
            <img src="https://picsum.photos/id/160/600/400" alt="代码格式化工具" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110" loading="lazy">
          </div>
          <div class="p-6">
            <div class="flex justify-between items-start mb-3">
              <span class="px-3 py-1 bg-cyan-100 text-cyan-600 text-sm font-medium rounded-full">开发工具</span>
              <div class="flex space-x-1">
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star-o text-yellow-400"></i>
              </div>
            </div>
            <h3 class="text-xl font-bold mb-2">多语言代码格式化工具</h3>
            <p class="text-gray-700 mb-4">支持多种编程语言的代码格式化、美化和压缩，提高代码可读性和开发效率。</p>
            <a href="#" class="inline-flex items-center text-blue-600 font-medium hover:text-blue-700 transition-colors">
              立即使用
              <i class="fa fa-external-link ml-1"></i>
            </a>
          </div>
        </div>
      </div>

      <!-- 工具卡片 4 -->
      <div class="tool-card" data-category="utilities">
        <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-xl hover:-translate-y-1">
          <div class="h-48 overflow-hidden">
            <img src="https://picsum.photos/id/20/600/400" alt="单位转换器" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110" loading="lazy">
          </div>
          <div class="p-6">
            <div class="flex justify-between items-start mb-3">
              <span class="px-3 py-1 bg-green-100 text-green-600 text-sm font-medium rounded-full">实用工具</span>
              <div class="flex space-x-1">
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star-half-o text-yellow-400"></i>
                <i class="fa fa-star-o text-yellow-400"></i>
              </div>
            </div>
            <h3 class="text-xl font-bold mb-2">全能单位转换器</h3>
            <p class="text-gray-700 mb-4">支持长度、重量、温度、面积、体积等多种单位转换，界面简洁，转换精准快速。</p>
            <a href="#" class="inline-flex items-center text-blue-600 font-medium hover:text-blue-700 transition-colors">
              立即使用
              <i class="fa fa-external-link ml-1"></i>
            </a>
          </div>
        </div>
      </div>

      <!-- 工具卡片 5 -->
      <div class="tool-card" data-category="productivity">
        <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-xl hover:-translate-y-1">
          <div class="h-48 overflow-hidden">
            <img src="https://picsum.photos/id/48/600/400" alt="在线倒计时工具" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110" loading="lazy">
          </div>
          <div class="p-6">
            <div class="flex justify-between items-start mb-3">
              <span class="px-3 py-1 bg-blue-100 text-blue-600 text-sm font-medium rounded-full">效率工具</span>
              <div class="flex space-x-1">
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star-half-o text-yellow-400"></i>
              </div>
            </div>
            <h3 class="text-xl font-bold mb-2">专注倒计时工具</h3>
            <p class="text-gray-700 mb-4">自定义时间、提醒方式和背景，帮助你保持专注，提高工作和学习效率。</p>
            <a href="#" class="inline-flex items-center text-blue-600 font-medium hover:text-blue-700 transition-colors">
              立即使用
              <i class="fa fa-external-link ml-1"></i>
            </a>
          </div>
        </div>
      </div>

      <!-- 工具卡片 6 -->
      <div class="tool-card" data-category="development">
        <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-all duration-300 hover:shadow-xl hover:-translate-y-1">
          <div class="h-48 overflow-hidden">
            <img src="https://picsum.photos/id/119/600/400" alt="JSON格式化工具" class="w-full h-full object-cover transition-transform duration-500 hover:scale-110" loading="lazy">
          </div>
          <div class="p-6">
            <div class="flex justify-between items-start mb-3">
              <span class="px-3 py-1 bg-cyan-100 text-cyan-600 text-sm font-medium rounded-full">开发工具</span>
              <div class="flex space-x-1">
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star text-yellow-400"></i>
                <i class="fa fa-star-o text-yellow-400"></i>
              </div>
            </div>
            <h3 class="text-xl font-bold mb-2">JSON格式化与验证工具</h3>
            <p class="text-gray-700 mb-4">快速格式化JSON数据，提供语法验证和错误提示，支持压缩和美化两种模式。</p>
            <a href="#" class="inline-flex items-center text-blue-600 font-medium hover:text-blue-700 transition-colors">
              立即使用
              <i class="fa fa-external-link ml-1"></i>
            </a>
          </div>
        </div>
      </div>
    </div>

    <!-- 加载更多按钮 -->
    <div class="text-center mt-12">
      <button id="load-more" class="px-6 py-3 border border-blue-600 text-blue-600 hover:bg-blue-600 hover:text-white font-medium rounded-lg transition-all duration-300">
        加载更多工具
        <i class="fa fa-refresh ml-2"></i>
      </button>
    </div>
  </div>
</section>

<!-- 关于我区域 -->
<section id="about" class="py-16 md:py-24 bg-gradient-to-r from-blue-50 to-purple-50 rounded-t-3xl rounded-b-3xl">
  <div class="container mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex flex-col md:flex-row items-center">
      <div class="md:w-1/3 mb-10 md:mb-0 md:pr-8">
        <div class="relative">
          <div class="absolute -inset-4 bg-gradient-to-r from-blue-100 to-purple-100 rounded-full blur-xl opacity-70"></div>
          <img src="https://picsum.photos/id/64/300/300" alt="个人头像" class="relative w-64 h-64 rounded-full object-cover shadow-xl border-4 border-white" loading="lazy">
        </div>
      </div>
      <div class="md:w-2/3">
        <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold mb-4">关于我</h2>
        <p class="text-gray-700 text-lg mb-6">
          你好！我是一名热爱编程和创造的开发者，喜欢制作各种实用的小工具来解决日常工作和生活中的问题。
        </p>
        <p class="text-gray-700 text-lg mb-6">
          我相信好的工具能够极大地提升效率，让我们有更多时间专注于更有价值的事情。这个网站收集了我开发的各类小工具，希望能够帮助到有需要的人。
        </p>
        <p class="text-gray-700 text-lg mb-8">
          如果你有任何建议或需求，欢迎联系我，我会不断优化现有工具并开发更多实用的新工具。
        </p>
        <div class="flex flex-wrap gap-4">
          <a href="https://github.com/yourusername" target="_blank" class="inline-flex items-center px-4 py-2 bg-blue-600 hover:bg-blue-700 text-white font-medium rounded-lg shadow-md transition-all duration-300">
            <i class="fa fa-github mr-2"></i> GitHub
          </a>
          <a href="#contact" class="inline-flex items-center px-4 py-2 bg-gray-200 hover:bg-gray-300 text-gray-800 font-medium rounded-lg transition-all duration-300">
            <i class="fa fa-envelope mr-2"></i> 联系我
          </a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 联系区域 -->
<section id="contact" class="py-16 md:py-24">
  <div class="container mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16">
      <h2 class="text-[clamp(1.8rem,4vw,2.5rem)] font-bold mb-4">联系我</h2>
      <p class="text-gray-700 max-w-2xl mx-auto text-lg">
        有任何问题、建议或合作意向，欢迎通过以下方式联系我
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
      <!-- 联系表单 -->
      <div class="bg-white p-8 rounded-xl shadow-lg">
        <h3 class="text-xl font-bold mb-6">发送消息</h3>
        <form action="#" method="post">
          <div class="mb-4">
            <label for="name" class="block text-gray-800 font-medium mb-2">姓名</label>
            <input type="text" id="name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors" placeholder="请输入你的姓名" required>
          </div>
          <div class="mb-4">
            <label for="email" class="block text-gray-800 font-medium mb-2">邮箱</label>
            <input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors" placeholder="请输入你的邮箱" required>
          </div>
          <div class="mb-4">
            <label for="message" class="block text-gray-800 font-medium mb-2">消息内容</label>
            <textarea id="message" rows="4" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition-colors" placeholder="请输入你的消息内容" required></textarea>
          </div>
          <button type="submit" class="w-full py-3 bg-blue-600 hover:bg-blue-700 text-white font-medium rounded-lg shadow-md hover:shadow-lg transition-all duration-300">
            发送消息
          </button>
        </form>
      </div>

      <!-- 联系信息 -->
      <div class="flex flex-col justify-center">
        <div class="mb-8">
          <h3 class="text-xl font-bold mb-4">联系方式</h3>
          <div class="space-y-4">
            <a href="mailto:example@mail.com" class="flex items-center text-gray-700 hover:text-blue-600 transition-colors">
              <i class="fa fa-envelope text-xl w-8 text-blue-600"></i>
              <span>example@mail.com</span>
            </a>
            <a href="https://github.com/yourusername" target="_blank" class="flex items-center text-gray-700 hover:text-blue-600 transition-colors">
              <i class="fa fa-github text-xl w-8 text-blue-600"></i>
              <span>github.com/yourusername</span>
            </a>
            <a href="https://twitter.com/yourusername" target="_blank" class="flex items-center text-gray-700 hover:text-blue-600 transition-colors">
              <i class="fa fa-twitter text-xl w-8 text-blue-600"></i>
              <span>twitter.com/yourusername</span>
            </a>
          </div>
        </div>

        <div>
          <h3 class="text-xl font-bold mb-4">关注我</h3>
          <div class="flex space-x-4">
            <a href="https://github.com/yourusername" target="_blank" class="w-12 h-12 rounded-full bg-blue-50 flex items-center justify-center text-blue-600 hover:bg-blue-600 hover:text-white transition-all duration-300">
              <i class="fa fa-github text-xl"></i>
            </a>
            <a href="https://twitter.com/yourusername" target="_blank" class="w-12 h-12 rounded-full bg-blue-50 flex items-center justify-center text-blue-600 hover:bg-blue-600 hover:text-white transition-all duration-300">
              <i class="fa fa-twitter text-xl"></i>
            </a>
            <a href="https://linkedin.com/in/yourusername" target="_blank" class="w-12 h-12 rounded-full bg-blue-50 flex items-center justify-center text-blue-600 hover:bg-blue-600 hover:text-white transition-all duration-300">
              <i class="fa fa-linkedin text-xl"></i>
            </a>
            <a href="https://instagram.com/yourusername" target="_blank" class="w-12 h-12 rounded-full bg-blue-50 flex items-center justify-center text-blue-600 hover:bg-blue-600 hover:text-white transition-all duration-300">
              <i class="fa fa-instagram text-xl"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- 返回顶部按钮 -->
<button id="back-to-top" class="fixed bottom-8 right-8 bg-blue-600 text-white w-12 h-12 rounded-full shadow-lg flex items-center justify-center opacity-0 invisible transition-all duration-300 hover:bg-blue-700 z-50">
  <i class="fa fa-arrow-up"></i>
</button>

<!-- JavaScript -->
<script>
// 等待页面加载完成
document.addEventListener('DOMContentLoaded', function() {
  // 导航栏滚动效果
  const navbar = document.querySelector('.site-nav');
  const backToTop = document.getElementById('back-to-top');
  
  window.addEventListener('scroll', () => {
    if (window.scrollY > 100) {
      if (navbar) navbar.classList.add('shadow-md');
      backToTop.classList.remove('opacity-0', 'invisible');
      backToTop.classList.add('opacity-100', 'visible');
    } else {
      if (navbar) navbar.classList.remove('shadow-md');
      backToTop.classList.add('opacity-0', 'invisible');
      backToTop.classList.remove('opacity-100', 'visible');
    }
  });
  
  // 平滑滚动
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      
      const targetId = this.getAttribute('href');
      if (targetId === '#') return;
      
      const targetElement = document.querySelector(targetId);
      if (targetElement) {
        window.scrollTo({
          top: targetElement.offsetTop - 80,
          behavior: 'smooth'
        });
      }
    });
  });
  
  // 返回顶部
  backToTop.addEventListener('click', () => {
    window.scrollTo({
      top: 0,
      behavior: 'smooth'
    });
  });
  
  // 工具筛选功能
  const filterButtons = document.querySelectorAll('.tool-filter');
  const toolCards = document.querySelectorAll('.tool-card');
  
  filterButtons.forEach(button => {
    button.addEventListener('click', () => {
      // 更新按钮样式
      filterButtons.forEach(btn => {
        btn.classList.remove('active', 'bg-blue-600', 'text-white');
        btn.classList.add('bg-gray-100', 'hover:bg-gray-200');
      });
      
      button.classList.add('active', 'bg-blue-600', 'text-white');
      button.classList.remove('bg-gray-100', 'hover:bg-gray-200');
      
      const category = button.getAttribute('data-category');
      
      // 筛选工具卡片
      toolCards.forEach(card => {
        if (category === 'all' || card.getAttribute('data-category') === category) {
          card.style.display = 'block';
          // 添加淡入动画
          setTimeout(() => {
            card.style.opacity = '1';
            card.style.transform = 'translateY(0)';
          }, 50);
        } else {
          // 添加淡出动画
          card.style.opacity = '0';
          card.style.transform = 'translateY(20px)';
          setTimeout(() => {
            card.style.display = 'none';
          }, 300);
        }
      });
    });
  });
  
  // 加载更多按钮效果
  const loadMoreBtn = document.getElementById('load-more');
  let isLoading = false;
  
  loadMoreBtn.addEventListener('click', () => {
    if (isLoading) return;
    
    isLoading = true;
    loadMoreBtn.innerHTML = '<i class="fa fa-spinner fa-spin mr-2"></i> 加载中...';
    
    // 模拟加载延迟
    setTimeout(() => {
      loadMoreBtn.innerHTML = '没有更多工具了 <i class="fa fa-check ml-2"></i>';
      loadMoreBtn.disabled = true;
      loadMoreBtn.classList.add('opacity-50', 'cursor-not-allowed');
      loadMoreBtn.classList.remove('hover:bg-blue-600', 'hover:text-white');
      isLoading = false;
    }, 1500);
  });
  
  // 初始化卡片动画
  toolCards.forEach((card, index) => {
    setTimeout(() => {
      card.style.opacity = '1';
      card.style.transform = 'translateY(0)';
    }, 100 * index);
  });
});
</script>

<!-- 自定义样式 -->
<style>
.tool-card {
  opacity: 0;
  transform: translateY(20px);
  transition: opacity 0.3s ease, transform 0.3s ease;
}

/* 适配 Minimal Mistakes 主题的额外样式 */
.site-nav {
  transition: all 0.3s ease;
}

.bg-gradient-to-r {
  background-image: linear-gradient(to right, var(--tw-gradient-stops));
}

.from-blue-50 {
  --tw-gradient-from: #eff6ff;
  --tw-gradient-to: rgba(239, 246, 255, 0);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.to-purple-50 {
  --tw-gradient-to: #faf5ff;
}

.animate-pulse {
  animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

@keyframes pulse {
  0%, 100% {
    opacity: 1;
  }
  50% {
    opacity: 0.5;
  }
}
</style>