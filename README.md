import {
  ArrowUpLeft,
  BarChart3,
  CheckCircle2,
  CircleHelp,
  LayoutTemplate,
  MessageCircle,
  MousePointerClick,
  Phone,
  Search,
  Settings2,
  ShoppingBag,
  Sparkles,
  Store,
  TrendingUp,
  UserRound,
} from "lucide-react";

export default function BriefAgencyWebLandingPage() {
  const navItems = ["عن بريف ايجنسي", "خدماتنا", "أعمالنا", "شركاؤنا", "تواصل معنا"];

  const painPoints = [
    "تصميم جميل.. لكنه لا يقود إلى نتيجة.",
    "تجربة استخدام مربكة.. لا تدفع العميل لإكمال اهتمامه.",
    "رسائل غير واضحة.. لا تشرح القيمة الحقيقية.",
    "صفحات لا توجه الزائر نحو خطوة محددة.",
  ];

  const solutions = [
    "يقدّم رسالتك بوضوح من اللحظة الأولى",
    "يقنع عميلك ويحوّل زيارته إلى خطوة شراء مباشرة",
    "منظّم بهيكل مدروس يسهل التصفح",
    "سهل الاستخدام ويختصر الطريق على العميل",
    "ومبني ليقود كل زيارة نحو قرار واضح",
  ];

  const features = [
    {
      icon: Search,
      title: "سؤال وتحليل",
      text: "نستكشف الثغرات وحقائق الجمهور والفرص الحقيقية قبل أي قرار تصميمي.",
    },
    {
      icon: LayoutTemplate,
      title: "تخطيط وتأسيس",
      text: "رسائل دقيقة، هيكل واضح، وأصول بصرية جاهزة لرحلة استخدام أكثر إقناعًا.",
    },
    {
      icon: TrendingUp,
      title: "تفعيل وتحسين",
      text: "نطلق الموقع أو المتجر ونحسن التجربة باستمرار وفق البيانات والسلوك الفعلي.",
    },
    {
      icon: BarChart3,
      title: "توسيع ونمو",
      text: "نستثمر النتائج ونبني على ما نجح لتوسيع الأثر ورفع فرص التحويل.",
    },
  ];

  const process = [
    {
      step: "01",
      title: "دراسة المشروع",
      text: "نفهم أهداف المشروع وطبيعته ونحدد ما الذي يجب أن يراه العميل ويشعر به منذ اللحظة الأولى.",
    },
    {
      step: "02",
      title: "تحليل الجمهور والمنافسين",
      text: "نكتشف الفرص ونقاط التميز ونبني تجربة أقرب لما يبحث عنه العميل فعلًا.",
    },
    {
      step: "03",
      title: "تصميم تجربة المستخدم",
      text: "نرتب المحتوى والمسارات والواجهات بحيث تصبح الرحلة أوضح وأسهل وأكثر إقناعًا.",
    },
    {
      step: "04",
      title: "التطوير والتهيئة",
      text: "نحوّل التصميم إلى موقع أو متجر سريع وواضح ومتوافق مع أفضل الممارسات التقنية.",
    },
    {
      step: "05",
      title: "المراجعة والتحسين",
      text: "نراجع الأداء ونعالج التفاصيل النهائية لضمان جاهزية كاملة قبل الاعتماد النهائي.",
    },
  ];

  const stats = [
    {
      icon: UserRound,
      value: "+90",
      accent: "من العملاء",
      label: "استمروا معنا لأكثر من 6 أشهر",
    },
    {
      icon: Settings2,
      value: "+40",
      accent: "مشروع نُفذ",
      label: "عبر قطاعات مختلفة",
    },
    {
      icon: Sparkles,
      value: "+85%",
      accent: "تحسن في أداء",
      label: "الحملات خلال أول 90 يوم",
    },
    {
      icon: ShoppingBag,
      value: "-35%",
      accent: "انخفاض في تكلفة",
      label: "اكتساب العميل (CAC)",
    },
    {
      icon: MousePointerClick,
      value: "+8x",
      accent: "العائد على",
      label: "الإنفاق الإعلاني (ROAS)",
    },
  ];

  return (
    <div dir="rtl" className="min-h-screen bg-[#f3f4f6] text-[#101828]">
      <div className="fixed bottom-6 left-6 z-50 hidden flex-col gap-3 md:flex">
        <a
          href="#contact"
          className="flex h-14 w-14 items-center justify-center rounded-full bg-[#11B9F2] text-white shadow-[0_16px_40px_rgba(17,185,242,0.35)] transition hover:-translate-y-1"
        >
          <Phone className="h-6 w-6" />
        </a>
        <a
          href="#contact"
          className="flex h-14 w-14 items-center justify-center rounded-full bg-[#11B9F2] text-white shadow-[0_16px_40px_rgba(17,185,242,0.35)] transition hover:-translate-y-1"
        >
          <MessageCircle className="h-6 w-6" />
        </a>
      </div>

      <main className="relative overflow-hidden">
        <section className="relative bg-[#0667DB] pb-20 pt-6 md:pb-28 md:pt-8">
          <div className="absolute inset-0 opacity-30">
            <div className="absolute inset-x-10 top-0 h-full rounded-[40px] border border-white/25" />
            <div className="absolute left-1/2 top-0 h-full w-px -translate-x-1/2 bg-white/20" />
            <div className="absolute inset-y-0 left-10 w-px bg-white/20" />
            <div className="absolute inset-y-0 right-10 w-px bg-white/20" />
          </div>

          <div className="relative mx-auto max-w-7xl px-4 lg:px-8">
            <header className="rounded-[28px] bg-white px-6 py-5 shadow-[0_20px_60px_rgba(4,48,120,0.18)]">
              <div className="flex items-center justify-between gap-6">
                <div className="flex items-center gap-3 text-[#0B4FCB]">
                  <div className="text-right">
                    <div className="text-lg font-black leading-none">بريف ايجنسي</div>
                    <div className="mt-1 text-sm font-bold leading-none text-[#164CB8]">BRIEF AGENCY</div>
                  </div>
                  <div className="h-10 w-3 rounded-full bg-[#11B9F2]" />
                </div>

                <nav className="hidden items-center gap-8 text-sm font-bold text-[#1149B7] xl:flex">
                  {navItems.map((item) => (
                    <a key={item} href="#" className="transition hover:text-[#11B9F2]">
                      {item}
                    </a>
                  ))}
                </nav>

                <a
                  href="#contact"
                  className="inline-flex items-center gap-2 rounded-2xl bg-[#0B4FCB] px-5 py-3 text-sm font-bold text-white transition hover:-translate-y-0.5"
                >
                  اطلب الخدمة الآن
                  <ArrowUpLeft className="h-4 w-4" />
                </a>
              </div>
            </header>

            <div className="grid items-center gap-14 px-2 pt-16 lg:grid-cols-[1.05fr_0.95fr] lg:pt-20">
              <div>
                <div className="inline-flex rounded-full border border-white/20 bg-white/10 px-4 py-2 text-sm font-bold text-white backdrop-blur-sm">
                  خدمة تصميم وتطوير المواقع والمتاجر الإلكترونية
                </div>
                <h1 className="mt-6 max-w-3xl text-4xl font-black leading-[1.25] text-white md:text-5xl lg:text-7xl">
                  نبني تجربة رقمية متكاملة..
                  <span className="text-[#8AE6FF]"> تترجم إلى مبيعات</span>
                </h1>
                <p className="mt-6 max-w-2xl text-lg leading-9 text-white/85 md:text-xl">
                  متجرك أو موقعك الإلكتروني ليس مجرد واجهة رقمية، بل هو الانطباع الأول، والقرار الأول، والخطوة الأولى التي يتخذها العميل تجاهك.
                </p>
                <p className="mt-3 max-w-2xl text-lg leading-9 text-white/80">
                  نصمم ونطور متاجر إلكترونية ومواقع احترافية تعكس قيمة مشروعك، وتحوّل الزيارة إلى تفاعل حقيقي وشراء مباشر.
                </p>

                <div className="mt-9 flex flex-col gap-4 sm:flex-row">
                  <a
                    href="#contact"
                    className="inline-flex items-center justify-center gap-2 rounded-2xl bg-white px-7 py-4 text-base font-black text-[#0B4FCB] shadow-[0_16px_40px_rgba(0,0,0,0.18)] transition hover:-translate-y-1"
                  >
                    اطلب الخدمة الآن
                    <ArrowUpLeft className="h-5 w-5" />
                  </a>
                  <a
                    href="#process"
                    className="inline-flex items-center justify-center rounded-2xl border border-white/20 bg-white/10 px-7 py-4 text-base font-bold text-white backdrop-blur-sm transition hover:bg-white/15"
                  >
                    تعرّف على آلية العمل
                  </a>
                </div>

                <div className="mt-10 grid gap-3 sm:grid-cols-3">
                  {[
                    "تصميم يقود إلى نتيجة",
                    "تجربة استخدام واضحة",
                    "جاهزية تقنية واحترافية",
                  ].map((item) => (
                    <div
                      key={item}
                      className="rounded-2xl border border-white/15 bg-white/10 px-4 py-4 text-sm font-bold text-white/90 backdrop-blur-sm"
                    >
                      {item}
                    </div>
                  ))}
                </div>
              </div>

              <div className="relative">
                <div className="absolute -left-6 top-14 hidden h-24 w-24 rounded-[28px] bg-[#11B9F2]/15 blur-3xl lg:block" />
                <div className="rounded-[34px] border border-white/15 bg-white/10 p-4 shadow-[0_28px_60px_rgba(7,41,116,0.22)] backdrop-blur-sm">
                  <div className="rounded-[30px] bg-[#F7F8FA] p-5 md:p-6">
                    <div className="mb-5 flex items-center justify-between">
                      <div>
                        <div className="text-sm font-bold text-[#5D6B82]">واجهة رئيسية</div>
                        <div className="mt-1 text-lg font-black text-[#0C4ECC]">متجر / موقع احترافي</div>
                      </div>
                      <div className="rounded-full bg-[#11B9F2]/10 px-4 py-2 text-xs font-black text-[#11B9F2]">
                        Conversion Ready
                      </div>
                    </div>

                    <div className="grid gap-4 lg:grid-cols-[1.4fr_0.9fr]">
                      <div className="rounded-[28px] bg-[#0667DB] p-7 text-white">
                        <div className="mb-10 flex items-center justify-between text-xs font-bold text-white/65">
                          <span>Brief Agency</span>
                          <Store className="h-4 w-4" />
                        </div>
                        <div className="max-w-xs text-2xl font-black leading-relaxed md:text-[30px]">
                          نبني تجربة رقمية تقود العميل إلى القرار
                        </div>
                        <div className="mt-8 inline-flex items-center gap-2 rounded-2xl bg-white px-5 py-3 text-sm font-black text-[#0B4FCB]">
                          ابدأ الآن
                          <ArrowUpLeft className="h-4 w-4" />
                        </div>
                      </div>

                      <div className="space-y-4">
                        <div className="rounded-[24px] bg-white p-5 shadow-sm">
                          <div className="text-xs font-bold text-[#6A7688]">وضوح الرسالة</div>
                          <div className="mt-2 text-lg font-black text-[#0C4ECC]">+ أول انطباع أقوى</div>
                        </div>
                        <div className="rounded-[24px] bg-white p-5 shadow-sm">
                          <div className="text-xs font-bold text-[#6A7688]">سهولة المسار</div>
                          <div className="mt-2 text-lg font-black text-[#0C4ECC]">رحلة أبسط للعميل</div>
                        </div>
                        <div className="rounded-[24px] bg-[#11B9F2] p-5 text-white shadow-sm">
                          <div className="text-xs font-bold text-white/75">الهدف النهائي</div>
                          <div className="mt-2 text-lg font-black">تحويل الزيارة إلى إجراء</div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div className="relative mt-16 grid gap-6 md:grid-cols-2 xl:grid-cols-4">
              {features.map((item) => {
                const Icon = item.icon;
                return (
                  <div
                    key={item.title}
                    className="rounded-[30px] bg-white px-8 pb-8 pt-7 text-center shadow-[0_22px_60px_rgba(6,53,130,0.22)]"
                  >
                    <div className="mx-auto flex h-16 w-16 -translate-y-1 items-center justify-center rounded-[20px] bg-[#11B9F2] text-white shadow-lg">
                      <Icon className="h-7 w-7" />
                    </div>
                    <div className="mt-5 text-[26px] font-black leading-none text-[#0B4FCB]">{item.title}</div>
                    <p className="mt-4 text-base leading-8 text-[#384152]">{item.text}</p>
                  </div>
                );
              })}
            </div>
          </div>
        </section>

        <section className="bg-[#F3F4F6] py-24">
          <div className="mx-auto max-w-7xl px-6 lg:px-8">
            <div className="text-center">
              <div className="text-5xl font-black text-[#0B4FCB] md:text-6xl">أرقامنا</div>
              <div className="mt-5 text-2xl font-black text-[#111827] md:text-4xl">قيمة تُرى .. لا وعود تُقال</div>
            </div>

            <div className="mt-16 grid gap-8 md:grid-cols-2 xl:grid-cols-5">
              {stats.map((item) => {
                const Icon = item.icon;
                return (
                  <div key={item.value + item.label} className="text-center">
                    <div className="mx-auto flex h-20 w-20 items-center justify-center rounded-[24px] bg-[#11B9F2] text-white shadow-[0_16px_40px_rgba(17,185,242,0.28)]">
                      <Icon className="h-9 w-9" />
                    </div>
                    <div className="mt-5 text-5xl font-black leading-none text-[#0B4FCB]">{item.value}</div>
                    <div className="mt-4 text-xl font-black leading-8 text-[#111827]">
                      <span className="text-[#11B9F2]">{item.accent}</span>
                    </div>
                    <div className="mx-auto mt-1 max-w-[210px] text-xl font-black leading-8 text-[#111827]">
                      {item.label}
                    </div>
                  </div>
                );
              })}
            </div>
          </div>
        </section>

        <section className="mx-auto max-w-7xl px-6 py-24 lg:px-8">
          <div className="grid gap-10 lg:grid-cols-[0.9fr_1.1fr] lg:items-start">
            <div>
              <div className="text-sm font-black text-[#11B9F2]">المشكلة</div>
              <h2 className="mt-3 text-3xl font-black leading-[1.45] text-[#0B4FCB] md:text-5xl">
                منتجك وخدمتك مميزة..
                <br />
                لكن حضورك الرقمي لا يعكس ذلك
              </h2>
              <p className="mt-6 max-w-md text-lg leading-9 text-[#4B5563]">
                ليس كل تصميم جميل يبيع، وليس كل موقع يبدو احترافيًا قادرًا على خلق أثر حقيقي في قرار العميل.
              </p>
              <div className="mt-8 rounded-[28px] bg-[#0B4FCB] p-7 text-white shadow-[0_20px_60px_rgba(11,79,203,0.22)]">
                <div className="text-sm font-bold text-white/70">النتيجة النهائية</div>
                <div className="mt-3 text-2xl font-black leading-relaxed md:text-3xl">
                  زوار دون تفاعل.. ومجهود دون عائد
                </div>
              </div>
            </div>

            <div className="grid gap-4 sm:grid-cols-2">
              {painPoints.map((item, index) => (
                <div
                  key={item}
                  className="rounded-[28px] border border-[#DCE5F5] bg-white p-6 shadow-[0_10px_30px_rgba(15,23,42,0.05)]"
                >
                  <div className="mb-6 inline-flex h-12 w-12 items-center justify-center rounded-2xl bg-[#11B9F2]/10 text-sm font-black text-[#11B9F2]">
                    0{index + 1}
                  </div>
                  <p className="text-lg font-black leading-9 text-[#152033]">{item}</p>
                </div>
              ))}
            </div>
          </div>
        </section>

        <section className="bg-[#0667DB] py-24">
          <div className="mx-auto grid max-w-7xl gap-8 px-6 lg:grid-cols-[1fr_0.95fr] lg:px-8">
            <div className="rounded-[34px] bg-white p-8 shadow-[0_24px_60px_rgba(7,41,116,0.18)] md:p-10">
              <div className="text-sm font-black text-[#11B9F2]">الحل</div>
              <h2 className="mt-3 text-3xl font-black leading-[1.45] text-[#0B4FCB] md:text-5xl">
                نصمم لك متجرًا أو موقعًا
                <br />
                يعمل بوضوح من اللحظة الأولى
              </h2>
              <div className="mt-8 grid gap-4">
                {solutions.map((item) => (
                  <div
                    key={item}
                    className="flex items-start gap-4 rounded-2xl border border-[#E6ECF8] bg-[#F8FAFD] px-5 py-4"
                  >
                    <CheckCircle2 className="mt-1 h-5 w-5 shrink-0 text-[#11B9F2]" />
                    <p className="text-base font-bold leading-8 text-[#344054]">{item}</p>
                  </div>
                ))}
              </div>
            </div>

            <div className="flex flex-col justify-between rounded-[34px] border border-white/10 bg-white/10 p-8 text-white backdrop-blur-sm md:p-10">
              <div>
                <div className="text-sm font-black text-[#8AE6FF]">منطق التصميم</div>
                <div className="mt-4 text-3xl font-black leading-[1.5] md:text-5xl">
                  نحن لا نبني واجهة جميلة فقط..
                  <br />
                  بل نبني مسارًا واضحًا للقرار
                </div>
                <p className="mt-6 text-base leading-9 text-white/80 md:text-lg">
                  كل جزء في الصفحة يجب أن يساعد العميل على الفهم والثقة والتحرك. لذلك يأتي التصميم هنا كأداة بيع ذكية، لا كغلاف بصري فقط.
                </p>
              </div>
              <div className="mt-10 rounded-[28px] border border-white/10 bg-white/10 p-6">
                <div className="text-sm font-bold text-white/65">النتيجة التي نستهدفها</div>
                <div className="mt-3 text-2xl font-black leading-9">
                  رسالة أوضح، تجربة أهدأ، وتفاعل أعلى من الزيارة الأولى
                </div>
              </div>
            </div>
          </div>
        </section>

        <section className="mx-auto max-w-5xl px-6 py-24 text-center lg:px-8">
          <div className="inline-flex rounded-full border border-[#11B9F2]/20 bg-[#11B9F2]/10 px-4 py-2 text-sm font-black text-[#11B9F2]">
            لماذا Brief Agency؟
          </div>
          <h2 className="mt-6 text-3xl font-black leading-[1.5] text-[#0B4FCB] md:text-6xl">
            لأننا ننطلق من فهم عميق
            <br />
            لاحتياج عميلك.. لا من قوالب جاهزة
          </h2>
          <p className="mx-auto mt-8 max-w-3xl text-lg leading-9 text-[#475467] md:text-xl">
            خبرتنا التسويقية تمكننا من تحليل ما يبحث عنه العميل فعلًا، وفهم نقاط الألم والدوافع، لنصمم تجربة رقمية تنطلق من جوهر احتياجه لا من افتراضات عامة أو جمالية فقط.
          </p>
          <div className="mx-auto mt-10 max-w-3xl rounded-[30px] border border-[#DCE5F5] bg-white p-8 text-xl font-black leading-10 text-[#111827] shadow-[0_10px_30px_rgba(15,23,42,0.05)] md:text-3xl">
            نحن لا نبني موقعًا فحسب..
            <span className="text-[#0B4FCB]"> بل نبني تجربة تخاطب العميل وتدفعه لاتخاذ القرار</span>
          </div>
        </section>

        <section id="process" className="bg-white py-24">
          <div className="mx-auto max-w-7xl px-6 lg:px-8">
            <div className="max-w-2xl">
              <div className="text-sm font-black text-[#11B9F2]">آلية العمل</div>
              <h2 className="mt-3 text-3xl font-black leading-[1.45] text-[#0B4FCB] md:text-5xl">
                منهجية مدروسة تبدأ بالفهم..
                <br />
                وتنتهي بنتائج قابلة للقياس
              </h2>
            </div>

            <div className="mt-12 grid gap-5 lg:grid-cols-5">
              {process.map((item) => (
                <div
                  key={item.step}
                  className="rounded-[30px] border border-[#DCE5F5] bg-[#F8FAFD] p-6 shadow-[0_10px_30px_rgba(15,23,42,0.04)]"
                >
                  <div className="text-sm font-black tracking-[0.2em] text-[#11B9F2]">{item.step}</div>
                  <div className="mt-5 text-xl font-black text-[#0B4FCB]">{item.title}</div>
                  <p className="mt-4 text-sm font-medium leading-8 text-[#475467]">{item.text}</p>
                </div>
              ))}
            </div>

            <div className="mt-10 rounded-[32px] bg-[#0667DB] px-6 py-8 text-center text-white shadow-[0_20px_60px_rgba(11,79,203,0.2)] md:px-8">
              <div className="text-2xl font-black leading-10 md:text-4xl">
                تواصل معنا لتصميم موقع يبيع ويقنع
              </div>
            </div>
          </div>
        </section>

        <section id="contact" className="px-6 pb-24 lg:px-8">
          <div className="mx-auto grid max-w-7xl gap-8 overflow-hidden rounded-[38px] bg-[#0667DB] p-8 text-white shadow-[0_24px_60px_rgba(11,79,203,0.22)] md:p-10 lg:grid-cols-[1fr_0.95fr]">
            <div>
              <div className="text-sm font-black text-[#8AE6FF]">الخطوة التالية</div>
              <h2 className="mt-4 text-3xl font-black leading-[1.45] md:text-6xl">
                جاهز تبني حضورًا رقميًا
                <br />
                يعكس قيمة مشروعك؟
              </h2>
              <p className="mt-6 max-w-xl text-lg leading-9 text-white/85">
                دعنا نفهم مشروعك، ونبني لك موقعًا أو متجرًا لا يبدو جيدًا فقط.. بل يعمل بوضوح ويقود إلى نتيجة.
              </p>
              <div className="mt-8 flex flex-wrap gap-3">
                <a
                  href="#"
                  className="inline-flex items-center justify-center gap-2 rounded-2xl bg-white px-6 py-4 text-base font-black text-[#0B4FCB] transition hover:-translate-y-1"
                >
                  اطلب الخدمة الآن
                  <ArrowUpLeft className="h-5 w-5" />
                </a>
                <a
                  href="#"
                  className="inline-flex items-center justify-center gap-2 rounded-2xl border border-white/20 bg-white/10 px-6 py-4 text-base font-black text-white transition hover:bg-white/15"
                >
                  راسلنا عبر واتساب
                  <MessageCircle className="h-5 w-5" />
                </a>
              </div>
            </div>

            <div className="rounded-[30px] bg-white p-6 text-[#101828] md:p-8">
              <div className="flex items-center gap-3">
                <div className="flex h-11 w-11 items-center justify-center rounded-2xl bg-[#11B9F2]/10 text-[#11B9F2]">
                  <CircleHelp className="h-5 w-5" />
                </div>
                <div>
                  <div className="text-xl font-black text-[#0B4FCB]">ابدأ بطلب الخدمة</div>
                  <div className="mt-1 text-sm leading-7 text-[#667085]">
                    اترك بياناتك وسنعاود التواصل معك خلال وقت قصير.
                  </div>
                </div>
              </div>

              <div className="mt-6 grid gap-4">
                {[
                  "الاسم",
                  "اسم المشروع / النشاط",
                  "رقم الجوال",
                  "نوع الخدمة",
                  "وصف مختصر للاحتياج",
                ].map((label, index) => (
                  <div key={label}>
                    <label className="mb-2 block text-sm font-black text-[#344054]">{label}</label>
                    {index === 4 ? (
                      <textarea
                        rows={4}
                        placeholder="اكتب نبذة قصيرة عن مشروعك أو هدفك من الموقع"
                        className="w-full rounded-2xl border border-[#D0D5DD] bg-[#F8FAFC] px-4 py-3 text-sm outline-none placeholder:text-[#98A2B3] focus:border-[#11B9F2]"
                      />
                    ) : (
                      <input
                        placeholder={`أدخل ${label}`}
                        className="w-full rounded-2xl border border-[#D0D5DD] bg-[#F8FAFC] px-4 py-3 text-sm outline-none placeholder:text-[#98A2B3] focus:border-[#11B9F2]"
                      />
                    )}
                  </div>
                ))}
              </div>

              <button className="mt-6 w-full rounded-2xl bg-[#0B4FCB] px-6 py-4 text-base font-black text-white transition hover:opacity-95">
                إرسال الطلب
              </button>
            </div>
          </div>
        </section>
      </main>
    </div>
  );
}
