import { useState } from "react";

const NAV_ITEMS = [
  { id: "dashboard", label: "Dashboard", icon: "⊞" },
  { id: "websites", label: "AI Websites", icon: "🌐" },
  { id: "ads", label: "Social Ads", icon: "📣" },
  { id: "reputation", label: "Reputation", icon: "⭐" },
  { id: "leads", label: "Leads & CRM", icon: "👥" },
  { id: "reports", label: "Reports", icon: "📊" },
];

const CLIENTS = [
  { name: "Sunrise Bakery", score: 92, status: "Active", website: "Live", ads: "Running", reviews: 4.8 },
  { name: "Peak Fitness Studio", score: 78, status: "Active", website: "Building", ads: "Paused", reviews: 4.5 },
  { name: "Urban Dental Clinic", score: 85, status: "Active", website: "Live", ads: "Running", reviews: 4.9 },
  { name: "Lakeview Realty", score: 61, status: "Needs Attention", website: "Draft", ads: "Off", reviews: 3.9 },
];

const AI_TEMPLATES = [
  { id: 1, name: "Restaurant & Cafe", img: "🍽️", desc: "Full menu, reservations, Google Maps integration", time: "~2 min" },
  { id: 2, name: "Fitness & Wellness", img: "💪", desc: "Class schedules, booking, trainer profiles", time: "~2 min" },
  { id: 3, name: "Medical & Dental", img: "🏥", desc: "Appointment booking, services, patient forms", time: "~2 min" },
  { id: 4, name: "Real Estate", img: "🏠", desc: "Property listings, agent profiles, inquiry forms", time: "~2 min" },
  { id: 5, name: "Retail & E-commerce", img: "🛍️", desc: "Product showcase, cart, WhatsApp integration", time: "~3 min" },
  { id: 6, name: "Professional Services", img: "💼", desc: "Portfolio, testimonials, contact & booking", time: "~2 min" },
];

const ADS_CAMPAIGNS = [
  { name: "Sunrise Bakery – Diwali Offers", platform: "Facebook", status: "Active", spend: "₹4,200", clicks: 1840, leads: 47, roi: "+320%" },
  { name: "Peak Fitness – New Year Promo", platform: "Instagram", status: "Paused", spend: "₹2,800", clicks: 960, leads: 28, roi: "+185%" },
  { name: "Urban Dental – Checkup Drive", platform: "Facebook + Insta", status: "Active", spend: "₹6,500", clicks: 3100, leads: 89, roi: "+410%" },
];

function StatCard({ label, value, sub, color }) {
  return (
    <div className="bg-white rounded-2xl p-5 shadow-sm border border-gray-100">
      <p className="text-sm text-gray-500">{label}</p>
      <p className={`text-3xl font-bold mt-1 ${color || "text-gray-800"}`}>{value}</p>
      {sub && <p className="text-xs text-green-500 mt-1">{sub}</p>}
    </div>
  );
}

function Badge({ text, type }) {
  const colors = {
    Active: "bg-green-100 text-green-700",
    Running: "bg-blue-100 text-blue-700",
    Live: "bg-emerald-100 text-emerald-700",
    Paused: "bg-yellow-100 text-yellow-700",
    "Needs Attention": "bg-red-100 text-red-700",
    Building: "bg-purple-100 text-purple-700",
    Draft: "bg-gray-100 text-gray-600",
    Off: "bg-red-100 text-red-500",
  };
  return (
    <span className={`text-xs px-2 py-0.5 rounded-full font-medium ${colors[text] || "bg-gray-100 text-gray-600"}`}>
      {text}
    </span>
  );
}

function ScoreBar({ score }) {
  const color = score >= 80 ? "bg-green-500" : score >= 60 ? "bg-yellow-400" : "bg-red-400";
  return (
    <div className="flex items-center gap-2">
      <div className="flex-1 bg-gray-100 rounded-full h-2">
        <div className={`${color} h-2 rounded-full`} style={{ width: `${score}%` }} />
      </div>
      <span className="text-sm font-semibold text-gray-700">{score}</span>
    </div>
  );
}

export default function App() {
  const [active, setActive] = useState("dashboard");
  const [buildingWebsite, setBuildingWebsite] = useState(null);
  const [built, setBuilt] = useState([]);
  const [creatingAd, setCreatingAd] = useState(false);
  const [adStep, setAdStep] = useState(0);
  const [sidebarOpen, setSidebarOpen] = useState(true);

  function startBuild(template) {
    setBuildingWebsite(template.id);
    setTimeout(() => {
      setBuilt((b) => [...b, template.id]);
      setBuildingWebsite(null);
    }, 2500);
  }

  return (
    <div className="flex h-screen bg-gray-50 font-sans overflow-hidden">
      {/* Sidebar */}
      <aside className={`${sidebarOpen ? "w-56" : "w-16"} bg-white border-r border-gray-100 flex flex-col transition-all duration-200 shrink-0`}>
        {/* Logo */}
        <div className="flex items-center gap-2 px-4 py-5 border-b border-gray-100">
          <div className="w-8 h-8 rounded-xl bg-gradient-to-br from-violet-600 to-indigo-600 flex items-center justify-center text-white font-bold text-sm shrink-0">A</div>
          {sidebarOpen && <span className="font-bold text-gray-800 text-sm">AIPlatform</span>}
        </div>
        <nav className="flex-1 py-4 space-y-1 px-2">
          {NAV_ITEMS.map((item) => (
            <button
              key={item.id}
              onClick={() => setActive(item.id)}
              className={`w-full flex items-center gap-3 px-3 py-2.5 rounded-xl text-sm transition-all ${
                active === item.id
                  ? "bg-violet-50 text-violet-700 font-semibold"
                  : "text-gray-500 hover:bg-gray-50 hover:text-gray-800"
              }`}
            >
              <span className="text-base">{item.icon}</span>
              {sidebarOpen && <span>{item.label}</span>}
            </button>
          ))}
        </nav>
        <div className="p-3 border-t border-gray-100">
          <div className="flex items-center gap-2">
            <div className="w-8 h-8 rounded-full bg-gradient-to-br from-pink-400 to-orange-400 flex items-center justify-center text-white text-xs font-bold shrink-0">A</div>
            {sidebarOpen && (
              <div className="min-w-0">
                <p className="text-xs font-semibold text-gray-800 truncate">Admin</p>
                <p className="text-xs text-gray-400 truncate">Agency Owner</p>
              </div>
            )}
          </div>
        </div>
      </aside>

      {/* Main */}
      <main className="flex-1 flex flex-col overflow-hidden">
        {/* Top Bar */}
        <header className="bg-white border-b border-gray-100 px-6 py-4 flex items-center justify-between shrink-0">
          <div className="flex items-center gap-3">
            <button onClick={() => setSidebarOpen(!sidebarOpen)} className="text-gray-400 hover:text-gray-700 text-xl">☰</button>
            <div>
              <h1 className="text-lg font-bold text-gray-800">
                {NAV_ITEMS.find((n) => n.id === active)?.label}
              </h1>
              <p className="text-xs text-gray-400">Welcome back, Admin</p>
            </div>
          </div>
          <div className="flex items-center gap-3">
            <div className="bg-violet-600 text-white text-xs px-3 py-1.5 rounded-lg font-medium">
              ✨ AI Powered
            </div>
            <button className="relative text-gray-400 hover:text-gray-700">
              🔔
              <span className="absolute -top-1 -right-1 w-4 h-4 bg-red-500 rounded-full text-white text-xs flex items-center justify-center">3</span>
            </button>
          </div>
        </header>

        {/* Page Content */}
        <div className="flex-1 overflow-y-auto p-6">

          {/* DASHBOARD */}
          {active === "dashboard" && (
            <div className="space-y-6">
              <div className="grid grid-cols-4 gap-4">
                <StatCard label="Total Clients" value="24" sub="↑ 3 this month" color="text-violet-600" />
                <StatCard label="Active Websites" value="18" sub="↑ 2 new live" color="text-blue-600" />
                <StatCard label="Ad Spend (Month)" value="₹1.4L" sub="↑ 12% ROI increase" color="text-orange-500" />
                <StatCard label="Leads Generated" value="312" sub="↑ 28% vs last month" color="text-green-600" />
              </div>

              {/* AI Insight Banner */}
              <div className="bg-gradient-to-r from-violet-600 to-indigo-600 rounded-2xl p-5 text-white flex items-center justify-between">
                <div>
                  <p className="text-sm opacity-80 mb-1">🤖 AI Insight</p>
                  <p className="font-semibold text-lg">4 clients need attention — low review scores detected</p>
                  <p className="text-sm opacity-70 mt-1">AI suggests launching reputation campaigns for Lakeview Realty</p>
                </div>
                <button className="bg-white text-violet-700 font-semibold text-sm px-4 py-2 rounded-xl hover:bg-violet-50">
                  Fix Now →
                </button>
              </div>

              {/* Client Table */}
              <div className="bg-white rounded-2xl shadow-sm border border-gray-100 overflow-hidden">
                <div className="px-5 py-4 border-b border-gray-100 flex justify-between items-center">
                  <h2 className="font-semibold text-gray-800">Client Overview</h2>
                  <button className="text-xs text-violet-600 font-medium">View All →</button>
                </div>
                <table className="w-full text-sm">
                  <thead>
                    <tr className="text-xs text-gray-400 border-b border-gray-50">
                      <th className="text-left px-5 py-3">Client</th>
                      <th className="text-left px-5 py-3">AI Score</th>
                      <th className="text-left px-5 py-3">Status</th>
                      <th className="text-left px-5 py-3">Website</th>
                      <th className="text-left px-5 py-3">Ads</th>
                      <th className="text-left px-5 py-3">Reviews</th>
                    </tr>
                  </thead>
                  <tbody>
                    {CLIENTS.map((c, i) => (
                      <tr key={i} className="border-b border-gray-50 hover:bg-gray-50 transition">
                        <td className="px-5 py-3 font-medium text-gray-800">{c.name}</td>
                        <td className="px-5 py-3 w-36"><ScoreBar score={c.score} /></td>
                        <td className="px-5 py-3"><Badge text={c.status} /></td>
                        <td className="px-5 py-3"><Badge text={c.website} /></td>
                        <td className="px-5 py-3"><Badge text={c.ads} /></td>
                        <td className="px-5 py-3">
                          <span className="text-yellow-500">★</span>
                          <span className="ml-1 font-medium">{c.reviews}</span>
                        </td>
                      </tr>
                    ))}
                  </tbody>
                </table>
              </div>
            </div>
          )}

          {/* AI WEBSITES */}
          {active === "websites" && (
            <div className="space-y-6">
              <div className="bg-gradient-to-r from-blue-600 to-cyan-500 rounded-2xl p-6 text-white">
                <p className="text-sm opacity-80 mb-1">🌐 AI Website Builder</p>
                <h2 className="text-2xl font-bold">Build a Professional Website in Minutes</h2>
                <p className="text-sm opacity-75 mt-2">AI automatically generates copy, images, and SEO — just pick a template</p>
              </div>

              <div className="grid grid-cols-3 gap-4">
                {AI_TEMPLATES.map((t) => (
                  <div key={t.id} className="bg-white rounded-2xl border border-gray-100 shadow-sm p-5 hover:shadow-md transition-all">
                    <div className="text-4xl mb-3">{t.img}</div>
                    <h3 className="font-semibold text-gray-800">{t.name}</h3>
                    <p className="text-xs text-gray-500 mt-1 mb-3">{t.desc}</p>
                    <div className="flex items-center justify-between">
                      <span className="text-xs text-gray-400">⏱ {t.time}</span>
                      {built.includes(t.id) ? (
                        <span className="text-xs bg-green-100 text-green-600 font-semibold px-3 py-1 rounded-lg">✓ Live</span>
                      ) : buildingWebsite === t.id ? (
                        <span className="text-xs bg-blue-100 text-blue-600 font-semibold px-3 py-1 rounded-lg animate-pulse">Building...</span>
                      ) : (
                        <button
                          onClick={() => startBuild(t)}
                          className="text-xs bg-violet-600 text-white font-semibold px-3 py-1.5 rounded-lg hover:bg-violet-700"
                        >
                          Build with AI
                        </button>
                      )}
                    </div>
                  </div>
                ))}
              </div>

              {built.length > 0 && (
                <div className="bg-green-50 border border-green-200 rounded-2xl p-4">
                  <p className="text-green-700 font-medium">✅ {built.length} website(s) built and live — AI has auto-filled content, SEO tags, and contact forms!</p>
                </div>
              )}
            </div>
          )}

          {/* SOCIAL ADS */}
          {active === "ads" && (
            <div className="space-y-6">
              <div className="bg-gradient-to-r from-orange-500 to-pink-500 rounded-2xl p-6 text-white flex items-center justify-between">
                <div>
                  <p className="text-sm opacity-80 mb-1">📣 AI Ad Manager</p>
                  <h2 className="text-2xl font-bold">Create & Launch Social Media Ads</h2>
                  <p className="text-sm opacity-75 mt-1">AI writes copy, designs creatives, targets audience automatically</p>
                </div>
                <button
                  onClick={() => { setCreatingAd(true); setAdStep(0); }}
                  className="bg-white text-orange-600 font-bold px-5 py-2.5 rounded-xl hover:bg-orange-50 shrink-0"
                >
                  + Create Campaign
                </button>
              </div>

              {/* Campaign creation wizard */}
              {creatingAd && (
                <div className="bg-white rounded-2xl border border-gray-100 shadow-sm p-6">
                  <div className="flex items-center gap-2 mb-5">
                    {["Business Info", "Platform", "AI Generate", "Launch"].map((s, i) => (
                      <div key={i} className="flex items-center gap-1">
                        <div className={`w-7 h-7 rounded-full flex items-center justify-center text-xs font-bold ${i <= adStep ? "bg-violet-600 text-white" : "bg-gray-100 text-gray-400"}`}>
                          {i < adStep ? "✓" : i + 1}
                        </div>
                        <span className={`text-xs ${i <= adStep ? "text-violet-600 font-medium" : "text-gray-400"}`}>{s}</span>
                        {i < 3 && <span className="text-gray-200 mx-1">›</span>}
                      </div>
                    ))}
                  </div>
                  {adStep === 0 && (
                    <div className="space-y-3">
                      <h3 className="font-semibold">Business Details</h3>
                      <input className="w-full border border-gray-200 rounded-xl px-4 py-2.5 text-sm" placeholder="Business Name" />
                      <input className="w-full border border-gray-200 rounded-xl px-4 py-2.5 text-sm" placeholder="Industry (e.g. Restaurant, Gym, Dental)" />
                      <input className="w-full border border-gray-200 rounded-xl px-4 py-2.5 text-sm" placeholder="Campaign Goal (e.g. Get leads, drive traffic)" />
                      <button onClick={() => setAdStep(1)} className="bg-violet-600 text-white px-5 py-2 rounded-xl text-sm font-medium">Next →</button>
                    </div>
                  )}
                  {adStep === 1 && (
                    <div className="space-y-3">
                      <h3 className="font-semibold">Select Platforms</h3>
                      <div className="grid grid-cols-3 gap-3">
                        {["Facebook", "Instagram", "Google Ads"].map((p) => (
                          <div key={p} className="border-2 border-violet-200 bg-violet-50 rounded-xl p-3 text-center cursor-pointer hover:border-violet-500">
                            <p className="text-sm font-medium text-violet-700">{p}</p>
                          </div>
                        ))}
                      </div>
                      <div className="flex gap-2">
                        <button onClick={() => setAdStep(0)} className="border border-gray-200 px-4 py-2 rounded-xl text-sm">← Back</button>
                        <button onClick={() => setAdStep(2)} className="bg-violet-600 text-white px-5 py-2 rounded-xl text-sm font-medium">Next →</button>
                      </div>
                    </div>
                  )}
                  {adStep === 2 && (
                    <div className="space-y-3">
                      <h3 className="font-semibold">🤖 AI Generated Ad Copy</h3>
                      <div className="bg-gray-50 rounded-xl p-4 border border-gray-100">
                        <p className="text-xs text-gray-400 mb-1">Headline</p>
                        <p className="font-semibold text-gray-800">"Get 30% Off This Season — Book Your Appointment Today!"</p>
                        <p className="text-xs text-gray-400 mt-3 mb-1">Body Copy</p>
                        <p className="text-sm text-gray-600">We're offering exclusive deals for new & existing customers. Don't miss out — limited slots available. Click below to book instantly!</p>
                        <p className="text-xs text-gray-400 mt-3 mb-1">Target Audience (AI Suggested)</p>
                        <p className="text-sm text-gray-600">Age 25–45 · 10 km radius · Interests: Health, Wellness, Local Services</p>
                      </div>
                      <div className="flex gap-2">
                        <button onClick={() => setAdStep(1)} className="border border-gray-200 px-4 py-2 rounded-xl text-sm">← Back</button>
                        <button onClick={() => setAdStep(3)} className="bg-violet-600 text-white px-5 py-2 rounded-xl text-sm font-medium">Looks Good →</button>
                      </div>
                    </div>
                  )}
                  {adStep === 3 && (
                    <div className="space-y-3 text-center">
                      <div className="text-5xl">🚀</div>
                      <h3 className="font-bold text-xl text-gray-800">Campaign Ready to Launch!</h3>
                      <p className="text-sm text-gray-500">AI has prepared your ad creative, copy, audience targeting, and budget allocation.</p>
                      <button onClick={() => { setCreatingAd(false); }} className="bg-gradient-to-r from-orange-500 to-pink-500 text-white px-8 py-3 rounded-xl font-bold text-sm hover:opacity-90">
                        🚀 Launch Campaign Now
                      </button>
                    </div>
                  )}
                </div>
              )}

              {/* Active Campaigns */}
              <div className="bg-white rounded-2xl border border-gray-100 shadow-sm overflow-hidden">
                <div className="px-5 py-4 border-b border-gray-100">
                  <h2 className="font-semibold text-gray-800">Active Campaigns</h2>
                </div>
                <table className="w-full text-sm">
                  <thead>
                    <tr className="text-xs text-gray-400 border-b border-gray-50">
                      <th className="text-left px-5 py-3">Campaign</th>
                      <th className="text-left px-5 py-3">Platform</th>
                      <th className="text-left px-5 py-3">Status</th>
                      <th className="text-left px-5 py-3">Spend</th>
                      <th className="text-left px-5 py-3">Clicks</th>
                      <th className="text-left px-5 py-3">Leads</th>
                      <th className="text-left px-5 py-3">ROI</th>
                    </tr>
                  </thead>
                  <tbody>
                    {ADS_CAMPAIGNS.map((c, i) => (
                      <tr key={i} className="border-b border-gray-50 hover:bg-gray-50">
                        <td className="px-5 py-3 font-medium text-gray-800">{c.name}</td>
                        <td className="px-5 py-3 text-gray-500">{c.platform}</td>
                        <td className="px-5 py-3"><Badge text={c.status} /></td>
                        <td className="px-5 py-3 font-medium">{c.spend}</td>
                        <td className="px-5 py-3 text-gray-600">{c.clicks.toLocaleString()}</td>
                        <td className="px-5 py-3 text-blue-600 font-semibold">{c.leads}</td>
                        <td className="px-5 py-3 text-green-600 font-bold">{c.roi}</td>
                      </tr>
                    ))}
                  </tbody>
                </table>
              </div>
            </div>
          )}

          {/* REPUTATION */}
          {active === "reputation" && (
            <div className="space-y-6">
              <div className="grid grid-cols-3 gap-4">
                <StatCard label="Avg. Rating" value="4.5★" sub="Across all clients" color="text-yellow-500" />
                <StatCard label="Total Reviews" value="1,284" sub="↑ 84 this month" color="text-blue-600" />
                <StatCard label="Response Rate" value="94%" sub="AI auto-replies enabled" color="text-green-600" />
              </div>
              <div className="bg-white rounded-2xl border border-gray-100 shadow-sm p-5">
                <h2 className="font-semibold text-gray-800 mb-4">Review Feed</h2>
                {[
                  { client: "Urban Dental Clinic", reviewer: "Rahul K.", rating: 5, text: "Excellent service! Very professional staff.", time: "2 hours ago", replied: true },
                  { client: "Sunrise Bakery", reviewer: "Priya M.", rating: 4, text: "Fresh pastries every day. Loved the ambiance!", time: "5 hours ago", replied: false },
                  { client: "Lakeview Realty", reviewer: "Amit S.", rating: 2, text: "Response time was slow. Could improve.", time: "Yesterday", replied: false },
                ].map((r, i) => (
                  <div key={i} className="border-b border-gray-50 last:border-0 py-4">
                    <div className="flex justify-between items-start">
                      <div>
                        <p className="text-xs text-violet-600 font-medium">{r.client}</p>
                        <p className="font-medium text-gray-800">{r.reviewer} <span className="text-yellow-400">{"★".repeat(r.rating)}{"☆".repeat(5 - r.rating)}</span></p>
                        <p className="text-sm text-gray-500 mt-1">{r.text}</p>
                        <p className="text-xs text-gray-400 mt-1">{r.time}</p>
                      </div>
                      {r.replied ? (
                        <span className="text-xs bg-green-100 text-green-600 px-2 py-1 rounded-lg">✓ Replied</span>
                      ) : (
                        <button className="text-xs bg-violet-600 text-white px-3 py-1.5 rounded-lg hover:bg-violet-700">AI Reply</button>
                      )}
                    </div>
                  </div>
                ))}
              </div>
            </div>
          )}

          {/* LEADS & CRM */}
          {active === "leads" && (
            <div className="space-y-6">
              <div className="grid grid-cols-4 gap-4">
                <StatCard label="New Leads" value="47" sub="This week" color="text-violet-600" />
                <StatCard label="Contacted" value="31" sub="65% contact rate" color="text-blue-600" />
                <StatCard label="Qualified" value="19" sub="61% qualify rate" color="text-orange-500" />
                <StatCard label="Converted" value="8" sub="42% close rate" color="text-green-600" />
              </div>
              <div className="bg-white rounded-2xl border border-gray-100 shadow-sm p-5">
                <h2 className="font-semibold text-gray-800 mb-4">Recent Leads</h2>
                {[
                  { name: "Deepak Sharma", source: "Facebook Ad", client: "Urban Dental", status: "Hot", time: "10 min ago" },
                  { name: "Neha Gupta", source: "Website Form", client: "Peak Fitness", status: "Warm", time: "1 hr ago" },
                  { name: "Rohit Verma", source: "Google Ad", client: "Sunrise Bakery", status: "New", time: "3 hrs ago" },
                  { name: "Anita Joshi", source: "Instagram Ad", client: "Lakeview Realty", status: "Cold", time: "Yesterday" },
                ].map((l, i) => (
                  <div key={i} className="flex items-center justify-between border-b border-gray-50 last:border-0 py-3">
                    <div className="flex items-center gap-3">
                      <div className="w-9 h-9 rounded-full bg-gradient-to-br from-violet-400 to-indigo-400 flex items-center justify-center text-white text-sm font-bold">
                        {l.name[0]}
                      </div>
                      <div>
                        <p className="font-medium text-gray-800 text-sm">{l.name}</p>
                        <p className="text-xs text-gray-400">{l.source} · {l.client}</p>
                      </div>
                    </div>
                    <div className="flex items-center gap-3">
                      <span className={`text-xs px-2 py-0.5 rounded-full font-medium ${l.status === "Hot" ? "bg-red-100 text-red-600" : l.status === "Warm" ? "bg-orange-100 text-orange-600" : l.status === "New" ? "bg-blue-100 text-blue-600" : "bg-gray-100 text-gray-500"}`}>
                        {l.status}
                      </span>
                      <span className="text-xs text-gray-400">{l.time}</span>
                      <button className="text-xs bg-violet-600 text-white px-2.5 py-1 rounded-lg">Contact</button>
                    </div>
                  </div>
                ))}
              </div>
            </div>
          )}

          {/* REPORTS */}
          {active === "reports" && (
            <div className="space-y-6">
              <div className="bg-gradient-to-r from-gray-800 to-gray-600 rounded-2xl p-6 text-white">
                <p className="text-sm opacity-70 mb-1">📊 AI Reports</p>
                <h2 className="text-2xl font-bold">Auto-Generated Client Reports</h2>
                <p className="text-sm opacity-60 mt-1">AI compiles performance data and sends branded reports to clients automatically</p>
              </div>
              <div className="grid grid-cols-3 gap-4">
                {CLIENTS.map((c, i) => (
                  <div key={i} className="bg-white rounded-2xl border border-gray-100 shadow-sm p-5">
                    <h3 className="font-semibold text-gray-800">{c.name}</h3>
                    <div className="mt-3 space-y-2">
                      <div className="flex justify-between text-sm">
                        <span className="text-gray-500">AI Score</span>
                        <span className="font-bold text-violet-600">{c.score}/100</span>
                      </div>
                      <div className="flex justify-between text-sm">
                        <span className="text-gray-500">Reviews</span>
                        <span className="font-medium">★ {c.reviews}</span>
                      </div>
                      <div className="flex justify-between text-sm">
                        <span className="text-gray-500">Website</span>
                        <Badge text={c.website} />
                      </div>
                      <div className="flex justify-between text-sm">
                        <span className="text-gray-500">Ads</span>
                        <Badge text={c.ads} />
                      </div>
                    </div>
                    <button className="mt-4 w-full text-xs bg-gray-800 text-white py-2 rounded-xl hover:bg-gray-700">
                      📄 Generate Report
                    </button>
                  </div>
                ))}
              </div>
            </div>
          )}

        </div>
      </main>
    </div>
  );
}
